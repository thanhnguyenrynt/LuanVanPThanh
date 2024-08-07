# LATEX CHO LUẬN VĂN CAO HỌC

## CÁC FORMAT ĐÃ ĐƯỢC ĐỊNH DẠNG SẴN. PROJECT ĐƯỢC CÀI ĐẶT CHẠY TRÊN VSCODE

> link hướng dẫn cài đặt [Cài đặt] (https://mathjiajia.github.io/vscode-and-latex/)

> Thực hiện build trên file the.tex

> Các chương nằm ở thư mục chapters. Các hình ảnh ở thư mục images

> Các trích dẫn nằm ở file refs.bib. Tìm các trích dẫn ở google scolar hoặc các web bài báo.

> Link [Github] (https://github.com/thanhnguyenrynt/LuanVanPThanh)
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
>Ví dụ về một hình ảnh
```latex
\begin{figure}[H]
	\centering
	\includegraphics[width=0.8\textwidth]{mobinet.png}
	\caption{Kiến trúc mô hình SSD MobileNetv2}
	\label{fig:mobinet}
\end{figure}
```

>[!TIP] 
>Ví dụ về một table
```latex

\begin{table}[h!]
    \centering
    \begin{threeparttable}
        \caption{Kết quả thể hiện độ cải thiện của mô hình YOLOv8 khi bổ sung ảnh nền}
        \begin{tabular}{lrrrrr}
            \hline
            \multicolumn{1}{l}{\textbf{\#}} & \textbf{Kim Loại} & \textbf{Giấy} & \textbf{Nhựa - Nilon} & \textbf{Khác} & \textbf{Tất cả} \\ \hline
            Tập dữ liệu                     & 0,377             & 0,415         & 0,553                 & 0,207         & 0,388           \\ \hline
            Tập bổ sung nền                 & 0,514             & 0,451         & 0,556                 & 0,263         & 0,446           \\ \hline
            Độ cải thiện                    & +0,13             & +0,036        & +0,003                & +0,056        & +0,058          \\ \hline
        \end{tabular}
        \label{tab:thaoluan1}
    \end{threeparttable}
\end{table}
```


>[!TIP] 
>Thắc mắc liên hệ email nguyenphuongthanh0410@gmail.com