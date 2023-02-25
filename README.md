# Stepps
## Entrevista segunda etapa, treinamento de um modelo de contagem de mamões



Link do projeto com video  teste:


- https://drive.google.com/file/d/1XGZBUb9ZAQZi_mXxY5J6sD0NIxvyBZcb/view?usp=share_link

Link do projeto com imagem  teste:
- https://drive.google.com/file/d/1XGZBUb9ZAQZi_mXxY5J6sD0NIxvyBZcb/view?usp=share_link

O objetivo deste desafio é fazer uma CONTAGEM da quantidade de elementos alvo
presentes na tela, neste caso, são mamões. Como será feita a contagem, fica à
critério do(a) candidato(a). Poderá ser utilizado qualquer modelo ou método desde
que seja apresentado o código para validação do resultado obtido.
## Procedimentos

- Treinado usando yolov5 o dataset fornecido pela empresa resultando um best.pt
- a contagem foi realizada usando um modelo DeepSORT — Deep Learning applied to Object Tracking
- foram criados dois arquivos video.py e img.py para contagem e detecçao 




## Em python Virtual Env

Primeiro clonamos este repositorio:


```sh
git clone https://github.com/ernestoper/entrevistaStepps.git
cd entrevistaStepps

```

Depois criamos um ambiente virtual e activamos o ambiente Virtual:

```sh
python3 -m venv venv
source venv/bin/activate
```

Depois instalamos o yolov5 (não precisamos treinar pois já esta treinado)
```sh
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
```
instando dependencia do  modelo DeepSORT — Deep Learning applied to Object Tracking:
```sh
cd ..
pip install -r requirements.txt
```
agora podemos contar os mamões usando:
```sh
cd ..
python video.py
python img.py
```










## License

MIT
