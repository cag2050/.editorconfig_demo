// root：表明是最顶层的配置文件，发现设为true时，才会停止查找.editorconfig文件
root = true

[*]
// 编码格式，支持latin1、utf-8、utf-8-bom、utf-16be和utf-16le，不建议使用uft-8-bom
charset = utf-8
// tab为hard-tabs，space为soft-tabs
indent_style = space
// 设置整数表示规定每级缩进的列数和soft-tabs的宽度（译注：空格数）。如果设定为tab，则会使用tab_width的值（如果已指定）
indent_size = 4
// end_of_line：定义换行符，支持lf、cr和crlf
// mac、unix、linux，默认为 lf
end_of_line = lf
// 设为true表明使文件以一个空白行结尾，false反之
insert_final_newline = true
// 设为true表示会除去换行行首的任意空白字符，false反之
trim_trailing_whitespace = true
