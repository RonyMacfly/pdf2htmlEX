
Docker easy install 

```
sudo docker load < bwits_pdf2htmlex.tar.xz
```

Run

```
sudo docker run -ti --rm -v /home/user/Documents/pdfToHtml:/pdf bwits/pdf2htmlex pdf2htmlEX --zoom 1.3 file.pdf
```

