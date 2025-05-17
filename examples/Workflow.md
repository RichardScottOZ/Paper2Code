# grobid

```bash
 sudo apt install docker.io
sudo docker pull grobid/grobid:0.8.2
sudo docker run --rm  --init --ulimit core=0 -p 8070:8070 grobid/grobid:0.8.2
```

http://localhost:8070/

```python
python doc2json/grobid2json/process_pdf.py -i tests/pdf/Enabling_Scalable_Mineral_Exploration_Self-Supervision_and_Explainability.pdf -t temp_dir/ -o output_dir/
```
