# Tarea_2_Intro_IA

Tarea 2: Redes Neuronales, Introducción a la Inteligencia Aritificial - COM4402

Cristopher Acevedo Guajardo

Para utilizar el código y verificar los resultados que fueron presentados en el informe, sólo se debe cambiar la estructura/modelo de la red neuronal.
Para esto, se deben cambiar los parámetros según sea necesario:

Modelo para una red de una capa oculta y 10 neuronas ocultas, con función de activación ReLU o Tanh (cambiar el parámetro nn.ReLU() por nn.Tanh() en el código para cambiar la función de activación)
model = nn.Sequential(
          nn.Linear(64, 10),
          nn.ReLU(),
          nn.Linear(10,10),
        )
        
Modelo para una red de una capa oculta y 40 neuronas ocultas, con función de activación ReLU o Tanh
model = nn.Sequential(
          nn.Linear(64, 40),
          nn.ReLU(),
          nn.Linear(40,10),
        )
        
Modelo de una red de dos capas ocultas y 10 neuronas ocultas, con función de activación ReLU o Tanh
model = nn.Sequential(
          nn.Linear(64, 10),
          nn.ReLU(),
          nn.Linear(10,10),
          nn.ReLU(),
          nn.Linear(10,10)
        )
        
Modelo de una red de dos capas ocultas y 40 neuronas ocultas, con función de activación ReLU o Tanh
model = nn.Sequential(
          nn.Linear(64, 40),
          nn.ReLU(),
          nn.Linear(40,40),
          nn.ReLU(),
          nn.Linear(40,10)
        )
        
Luego de haber cambiado el modelo de la red neuronal que se quiera utilizar, es recomendable ejecutar el código desde el comienzo, para evitar re-entrenar un conjunto o sufrir de la pérdida de algún dato debido a la conexión.
