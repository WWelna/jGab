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

## License
 
Copyright (C) 2021 William Welna (wwelna@occultusterra.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
