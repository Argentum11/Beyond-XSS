# Beyond XSS

This is a repo for taking notes from [Beyond XSS：探索網頁前端資安宇宙](https://ithelp.ithome.com.tw/m/users/20091346/ironman/6155)

## limitations of frontend javascript

- prohibit actively reading/writing local files
- prohibit calling system APIs
  - we can only use APIs provided by the browser
- prohibited from accessing the content of other web pages.
  - Same-Origin Policy (SOP)
    - every website can modify its HTML, execute javascript, but should't access data from other websites
  - for example, it is unsafe for ```blog.huli.tw``` to access emails in ```mail.google.com```
