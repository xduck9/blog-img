## CDN加速访问github文件的方式（必须是public仓库）：
- load any GitHub release, commit, or branch
  
  format: ```https://cdn.jsdelivr.net/gh/$user/$repo@$version/$file_path```

  eg:
  ```
  https://gcore.jsdelivr.net/gh/xduck9/blog-img@master/20250801-01.jpg
  ```

- add / at the end to get a directory listing
  
  formmat: ```https://cdn.jsdelivr.net/gh/$user/$repo/```

  eg:
  ```
  https://gcore.jsdelivr.net/gh/xduck9/blog-img/
  ```

- alternative CDN domain
  - gcore.jsdelivr.net (top recommended,海内外速度都很稳定)
  - testingcf.jsdelivr.ne (second recommended,海内外速度也不错，但时快时慢不太稳定，supported by Cloudflare)
  - cdn.jsdmirror.com (海内很快，海外太慢，supported by 腾讯云EdgeOne,虽然宣称全球加速)
