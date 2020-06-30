Embedding Gatsby sources as Iframe

```shell
npm i
npm run build
cp -a public/. static/
gatsby clean
change 
  <iframe src="/test.html" title="dummy" style={{width:'800px',height:'600px'}}></iframe> to
  <iframe src="/index.html" title="dummy" style={{width:'800px',height:'600px'}}></iframe>
npm run build
npm run serve
```
