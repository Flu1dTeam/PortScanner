# PortScanner
All popular browsers allow websites to access pages on localhost. This can be used to scan for open ports and detect applications. It also opens up the possibility of CSRF on local pages.

## Example:
`<script src="http://localhost:5900" onload="alert('VNC')" onerror="alert('No VNC')"></script>`
