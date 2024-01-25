| Domain                | Site           | Host                |
| --------------------- | -------------- | ------------------- |
| jays.net              |                | Linode 45.79.55.126 |
|                       | podcasts       | YunoHost on Linode  |
|                       | brotherbemused | Netlify             |
| tif.report            |                | Linode 45.79.55.126 |
|                       | ne / nebraska  | Netlify             |
| foodnotbombs.us       |                | Linode 45.79.55.126 |
|                       | omaha          | Netlify             |
|                       | map            | Netlify             |
|                       | edmonton       | Netlify (theirs)    |
|                       | pdx            | Netlify (theirs)    |
| usshoustondive.com    |                | Linode 45.79.55.126 |
| rvtr.org              |                | Retired             |

```
svn checkout https://github.com/jhannah/admin/trunk/jays.net/etc/apache2/sites-available

Because git sparse checkout doesn't work the way I want it to:  :(
   http://jasonkarns.com/blog/subdirectory-checkouts-with-git-sparse-checkout/

sudo apache2ctl restart
```
