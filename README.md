# Joomla-Atum-Sidebar-fixed-on-scroll-using-CSS
The Sidebar Menu in Joomla 4! / Joomla 5! Atum Template will scroll up (Toggle Menu is open) and become invisible when the screen scrolls down.

By simply adding a simple CSS code, the Sidebar Menu will remain in its position when the screen is scrolled, ensuring it remains visible even when the screen scrolls down.


Please add the following CSS into ‎/media/templates/administrator/atum/css/user.css file (please create a user.css file if you don't have one already):

```
/* SIDEBAR MENU ~ fixed on scroll */

#wrapper:not(.closed) .sidebar-wrapper .sidebar-sticky {
  position: fixed; 
  top: 66px;
}
```

### This is the position when the screen on top position.
![Atum-Sidebar-fixed-on-scroll-1](https://github.com/user-attachments/assets/904a53bc-b9e3-4af3-8b2f-1f25729a5d64)


### This is the position when the screen scroll down, the Sidebar Menu will scroll up. The result if the screen continues to scroll down is that the Sidebar Menu will no longer be visible.
![Atum-Sidebar-fixed-on-scroll-2](https://github.com/user-attachments/assets/03e7f139-66d4-43d9-a03b-056ffa64383c)


### After adding a simple CSS code, the Sidebar Menu will remain visible even when the screen scrolls down.
![Atum-Sidebar-fixed-on-scroll-3](https://github.com/user-attachments/assets/247f4f8b-649b-4722-afb0-de112770b868)


Good luck!
Let me know if you encounter any problems.
