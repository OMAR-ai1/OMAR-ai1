import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
import tkinter as tk
from tkinter import messagebox
from datetime import datetime, timedelta

# دالة لتحديث العداد
def update_timer():
    now = datetime.now()
    time_left = birthday - now
    days_left, seconds_left = divmod(time_left.total_seconds(), 86400)
    hours_left, seconds_left = divmod(seconds_left, 3600)
    minutes_left, seconds_left = divmod(seconds_left, 60)

    if time_left.total_seconds() > 0:
        countdown_label.config(text=f"الوقت المتبقي حتى عيد الميلاد:\n{int(days_left)} يوم، {int(hours_left)} ساعة، {int(minutes_left)} دقيقة")
        window.after(1000, update_timer)
    else:
        countdown_label.config(text="عيد ميلاد سعيد!")
        messagebox.showinfo("مفاجأة!", "كل سنة وأنت طيب!")
        # هنا يمكن تشغيل موسيقى عيد الميلاد أو عرض صور

# تحديد تاريخ عيد الميلاد
birthday = datetime(2024, 11, 1, 0, 0, 0)  # ضع تاريخ عيد ميلاد والدك هنا

# إعداد نافذة البرنامج
window = tk.Tk()
window.title("تهنئة عيد ميلاد")
window.geometry("400x300")

# رسالة ترحيب
welcome_label = tk.Label(window, text="عيد ميلاد سعيد يا أبي!", font=("Arial", 20), pady=20)
welcome_label.pack()

# العداد التنازلي
countdown_label = tk.Label(window, text="", font=("Arial", 16))
countdown_label.pack()

# بدء التحديث
update_timer()

window.mainloop()
