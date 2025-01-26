set autoindent
 set number
  
  "自动补全括号
  autocmd FileType html,c,cpp,css,js inoremap <Enter><CR><CR><Up>
  inoremap ( ()<Left>
  inoremap [ []<Left>
  inoremap { {}<Left>
  inoremap " ""<Left>
  inoremap ' ''<Left>
  "针对HTML文件类型设置映射
  autocmd FileType html inorema < <></><Left>
         
