# LATEX CHO LUẬN VĂN CAO HỌC

## CÁC FORMAT ĐÃ ĐƯỢC ĐỊNH DẠNG SẴN. PROJECT ĐƯỢC CÀI ĐẶT CHẠY TRÊN VSCODE

> link hướng dẫn cài đặt [Cài đặt] (https://mathjiajia.github.io/vscode-and-latex/)

> Thực hiện build trên file the.tex

> Các chương nằm ở thư mục chapers. Các hình ảnh ở thư mục images

## CÁC LƯU Ý KHI FORMAT

> [!TIP] 
> Cần có khoảng cách khi viết một đoạn. Các đoạn sử dụng \bigskip
```latex
 {\fontsize{13}{12} \selectfont 
    
    Đây là một đoạn văn

    }
    
\bigskip
```

>[!TIP] 
>Ví đụ về một hình ảnh
```latex
\begin{figure}[H]
	\centering
	\includegraphics[width=0.8\textwidth]{mobinet.png}
	\caption{Kiến trúc mô hình SSD MobileNetv2}
	\label{fig:mobinet}
\end{figure}
```