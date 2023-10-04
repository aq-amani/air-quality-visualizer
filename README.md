# air-quality-visualizer
A simple project to visualize air quality metrics (PM2.5 and TVOCs) in my room.

### Motivation
- Smoking smells (regular cigarates and vapes) leak into my room from other rooms in the same building
- TVOC metric is good for detecting vapes/electronic cigarates, and PM2.5 metric is good for detecting regular cigarattes
  - [Reference(Japanese): 受動喫煙にお困りなら、こうしましょう](http://www.jstc.or.jp/uploads/uploads/files/information/JUDOK20210218-1.pdf)

### Device used for air quality monitoring
[Temtop LKC-1000S+2nd air quality monitor](https://temtopus.com/products/temtop-lkc-1000s-2nd-generation-professional-detector-with-hcho-pm2-5-pm10-tvoc?variant=40630103539760)

This device saves the different readings into csv files that can be exported

### Jupyter notebook with result graphs
[TVOC_PM2.5_graphs.ipynb](./TVOC_PM2.5_graphs.ipynb)

### Outcome
The spikes in the TVOC and PM2.5 graphs match the timing when someone is smoking in nearby rooms.
