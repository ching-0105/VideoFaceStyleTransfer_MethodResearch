# VideoFaceStyleTransfer_MethodResearch




Video1：DualStyleGAN 會針對每個frame的人臉做face alignment，可以看到右上方格中的人頭一直在變換角度。<br>
而右下方格轉換後的影片，髮流等細微結構一直在跳動，很不連續<br>

https://user-images.githubusercontent.com/99737139/196706791-2e826d98-f838-434c-846f-03105cff73b5.mp4

Video2：VToonify 的效果很流暢<br>

https://user-images.githubusercontent.com/99737139/202955691-52b22935-7c61-4301-99e1-ec6fe8e263d3.mp4


Video3：DualStyleGAN 轉換後的影片會忽略人臉周圍的其他部位（例如：手指、吸管）<br>

https://user-images.githubusercontent.com/99737139/196706941-c49d83f9-c788-4384-9412-7c5b05730d19.mp4

Video4：VToonify 保留了手和吸管（雖然有點透明化）<br>

https://user-images.githubusercontent.com/99737139/202954566-815955f1-ab6f-46d2-8c14-83969d82b68e.mp4


DualStyleGAN的轉換過程 <br>
<div align=center>
<img src="data/dualstylegan.jpg" width=1000>
</div>

<img src="data/dualstylegan_without_alignment.jpg" width=800>

結合 MediaPipe Selfie Segmentation 的功能：將人物與背景分離並換上其他背景，但我們發現邊緣處理不是很好

https://user-images.githubusercontent.com/99737139/202954740-b18e882a-8c18-4171-8bcf-0259931b8b70.mp4


https://user-images.githubusercontent.com/99737139/202955436-8382c872-90c4-4b31-8ce0-7d78229d313e.mp4




