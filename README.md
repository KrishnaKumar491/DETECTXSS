# DETECTXSS
detection and prevention of Cross Site Scripting attacks
In present-daytime, securing the web application against hacking is a big
challenge. one of the most common types of hacking technique to attack the
web application is Cross-Site Scripting(XSS). Cross-Site Scripting
vulnerabilities are being exploited by the attackers to steal web browser’s
resources such as cookies, credentials etc.. we build a python flask project
that detecting the types of Cross-Site Scripting (XSS) attacks and also log the
attack entry in the database we are using two regular expressions (regex)
patterns to detect two different types of XSS attacks that are reflected and
DOM-based XSS attacks. when a user submits a form, the application checks
the input for XSS attacks using the detect XSS() function if an attack is
detected, then user is blocked using mac address and block message is
returned. otherwise, the user is granted access and dashboard is returned in
the dashboard we add information about Reflected and DOM-based CrossSite-Scripting (XSS) attacks and bottom of dashboard we give a attacker list
button that button show attacker list along with the time and date, mac
address, attack type, username and password.
