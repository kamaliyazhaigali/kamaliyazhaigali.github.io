# [tryhack my first ever ctf Jeopardy format was in the end of july]
# [ Pwn, Web, Forensic, Crypto, Reverse, Misc and OSINT.]
# [Question that I almost solved was about account take over/password reset flow.Ineeded to change passsword or delete the account]
# [Tools- Burpe Suite]
# [What I tried - Tried several directions in parallel: looked for the account's username to attempt a direct login; checked cookies 
# for the possibility of hijacking another user's session; tried forced browsing — changing the URL to paths like 
# /admin looking for an admin panel. None of these approaches led to a result.]
# [Why I failed- Acted without a clear hypothesis — tried multiple attack vectors (session hijacking, forced browsing, account enumeration)
# without first identifying which vulnerability class actually matched this task's mechanics (a password reset flow). 
# Didn't document the process in real time, so I can't reconstruct the exact sequence of actions now.]
# [ What I would have changed that time,is try to follow structure to  not try everything in one task.Moreover,try to solve IDOR on the user_id/email parameter
# in the reset request, Host Header poisoning — something I'd already covered on PortSwigger)
# — so next time I check the statistically likely vulnerability for that flow type first, instead of guessing with cookies or forced browsing.]
# [What I have learned after this CTF: first this id first thing that increased my interest in this field and introduced me with cybersecurity and related fields.
# I have learbed many new stuff and found many useful apps.Got hands-on experience with Burp Suite in a live, unstructured scenario
# — different from following a guided PortSwigger lab, this required deciding what to test with no walkthrough.
# First real exposure to competitive CTF pressure and time constraints, 
# which showed me the gap between recognizing a vulnerability type in a lab and identifying it live under time pressure.]
