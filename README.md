# jGab
Unofficial API interface to Gab

## Usage Instructions
```
usage: jGab [-h] --Cookies COOKIES [--out OUT] [--auto-out] [--until UNTIL]
            {profile,followers,following,timeline,comments,photos,video,group_timeline,group_info}
            ...

named arguments:
  -h, --help             show this help message and exit
  --Cookies COOKIES, -c COOKIES
                         Gab Cookies File
  --out OUT, -o OUT      Output File, or stdout by default
  --auto-out, -ao        Outputs a  file  of  format:  <USERNAME>-<DATE  of
                         YYYYMMDDHHMM>-<COMMAND>.json.     For     example:
                         testuser-202101151200-following.json     (default:
                         false)
  --until UNTIL, -u UNTIL
                         Grab data until it reaches  or past specified date
                         in YYYYMMDDHHMM.  Default  is  14  days  (default:
                         202101010332)

commands:
  {profile,followers,following,timeline,comments,photos,video,group_timeline,group_info}

-Trust The Plan-
```
## Things that won't ever be implimented (To Prevent Abuse)
* Follow / Unfollow
* Posting
* Blocking / Unblocking
* Report
* Mute
* Private Messaging

## Release Notes
Until further notice, there will be no public releases of this tool. You may request a copy of this tool, and if I like you, I'd be willing to part with it. This is to prevent abuse of the information gathered using this tool for malicious purposes. The restrictive License this and all other tools relating to scraping and OSINT is to protect and and prevent such malicious abuse of this software by others. This software is freely available upon request to anyone doing academic research or any other forms of legitimate research.

## License
 
         ~~~ CONFIDENTIAL SOURCE CODE AND/OR SOFTWARE ~~~

Copyright (c) 2021 William H. Welna, All Rights Reserved.

NOTICE: All information contained herein is, and remains the
property of William H. Welna. The intellectual and technical concepts
contained herein are proprietary to William H. Welna and may be
covered by U.S. and Foreign Patents, patents in process, and are
protected by trade secret and/or copyright law. Dissemination of this
information or reproduction of this material is strictly forbidden
unless prior written permission is obtained from William H. Welna.
Access to the source code and/or software contained herein is hereby
forbidden to anyone except individuals who have executed
Confidentiality and Non-disclosure agreements explicitly covering
such access, or has prior written permision obtained from
William H. Welna.

The copyright notice above does not evidence any actual or intended 
publication or disclosure of this source code and/or software, which
includes information that is confidential and/or proprietary, and is
the property of, William H. Welna.

Publication and/or disclosure of this source code and/or software is
an automatic and irrevocable agreement by the publisher and/or
individual or company to pay a fee of $10,000 US Dollars to
William H. Welna. This is not negotiatable, and William H. Welna
reserves the right to enforce payment of this fee due to this
agreement at any time.

ANY REPRODUCTION, MODIFICATION, DISTRIBUTION, PUBLIC PERFORMANCE, OR
PUBLIC DISPLAY OF OR THROUGH USE OF THIS SOURCE CODE AND/OR SOFTWARE
WITHOUT THE EXPRESS WRITTEN CONSENT OF William H. Welna IS STRICTLY
PROHIBITED, AND IN VIOLATION OF APPLICABLE LAWS AND INTERNATIONAL
TREATIES. THE RECEIPT OR POSSESSION OF THIS SOURCE CODE, AND/OR
RELATED INFORMATION, AND/OR SOFTWARE DOES NOT CONVEY OR IMPLY ANY
RIGHTS TO REPRODUCE, DISCLOSE OR DISTRIBUTE ITS CONTENTS, OR TO
MANUFACTURE, USE, OR SELL ANYTHING THAT IT MAY DESCRIBE, IN WHOLE OR
IN PART.
