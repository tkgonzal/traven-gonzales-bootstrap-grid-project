# Bootstrap Grid Project by Traven Gonzales

A simple Mail UI made in Bootstrap by Traven Gonzales for Bay Valley Tech's Module 1 Bootstrap Grid Project

## Bootstrap Grid Breakpoint Responsive Behaviour

The following is an explanation of the general responsive behaviour of the main components of the project
at Bootstrap's screen size breakpoints as the screen gets smaller.

### Desktop/LG-Breakpoint

Here all columns of the Mail UI (the Navbar, Inbox Bar, and Message Panel) are expanded and in full display.

### Tablet/MD-Breapoint

Starting at this breakpoint the Navbar and its offcanvas comopnent collapse, reducing its size such that it
displays as a header featuring the Mail UI's logo as well as an offcanvas toggle button. The full navbar
can be viewed upon interacting with the toggle button wherein it appears as an offcanvas component.

The Inbox Bar and Message Panel then fill out the rest of the screen below the navbar header.

### Mobile/SM-Breakpoint

Starting at this breakpoint the Message Panel column disappears allowing the Inbox Bar to fill out the rest
of the screen below the Navbar header. Also in this breakpoint, "open" buttons appear on the messages in the 
Inbox Bar. Upon interaction, the viewer opens a message modal with components similar to the message panel.
As of now, all messages in the inbox view open the same message.