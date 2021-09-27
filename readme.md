# 香港理工大学文泉学堂 PDF 一键下载脚本 
## wenquan-pdf-download

**请自觉遵守法律法规，本脚本仅供学习参考，所有下载的 PDF 请在24小时内删除，请勿传播或进行营利，一切法律责任由用户自己承担，与本人无关**

_本项目是重度基于[文泉学堂 PDF 油猴脚本](https://github.com/Kevin0z0/wenquan-pdf-download)及[文泉书局导出 PDF](https://github.com/xxlllq/PDFBooks)修改而成，用于适配港理文泉学堂下载 PDF使用_
<br>
## 使用方法

- (跳过如已安装)安装 [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey-beta/gcalenpjmijncebpfijmoaglllgpjagf)
    1. 安装 [本站脚本](https://greasyfork.org/en/scripts/432593)
    2. 访问 [文泉学堂 - 香港理工大学知识库](https://lib-hkpu.wqxuetang.com)
    3. 找到目标文献，点击 **阅读**，比如这篇文章: [公共经济学](https://lib-hkpu.wqxuetang.com/book/5189)
    4. 通过检查 Tampermonkey 右上角角标是否显示 1，以了解本站脚本是否成功运行
    5. **单机 PDF 内容页**，自动触发从被点击页面开始下载，每 50页 会另存为一个 PDF 文件
    6. 下载第二个 PDF 文件时候 (如果目标文献超过50页)，浏览器会提示你是否允许下载多个文件，请点击**是**


- 更佳详细导出 PDF 文件说明请参考: [源文件 PDF 下载](https://github.com/xxlllq/PDFBooks/blob/main/README.md#%E6%BA%90%E6%96%87%E4%BB%B6pdf%E4%B8%8B%E8%BD%BD)