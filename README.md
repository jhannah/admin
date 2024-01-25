| Site                  | Host    |
| --------------------- | ------- |
| jays.net              | Netlify |
| tif.report            | Netlify |
| ne.tif.report         | Netlify |
| foodnotbombs.us       | Netlify |
| omaha.foodnotbombs.us | Netlify |
| usshoustondive.com    | Linode  |
| rvtr.org              | Retired |

```
svn checkout https://github.com/jhannah/admin/trunk/jays.net/etc/apache2/sites-available

Because git sparse checkout doesn't work the way I want it to:  :(
   http://jasonkarns.com/blog/subdirectory-checkouts-with-git-sparse-checkout/

sudo apache2ctl restart
```
