# PortScanner
All popular browsers allow websites to access pages on localhost. This can be used to scan for open ports and detect applications. It also opens up the possibility of CSRF on local pages.

NOTE: Not all open ports are detectable. Some examples include SSH and SMTP. As a general rule, only ports you can access by typing http://localhost:port in your browser are detectable.

## Example:
`<script src="http://localhost:5900" onload="alert('VNC')" onerror="alert('No VNC')"></script>`
