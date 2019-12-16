# EEG-DWT-NeuralNetwork-PSO
En el presente trabajo se optimizan los hiperparámetros de una red neuronal del tipo Perceptrón Multicapa (MLP) con el algoritmo PSO (Optimizacíón por enjambre de partículas).

Los hiperparámetros que se optimizan son la función de activación, el numero de capas ocultas, el numero de neuronas en cada capa oculta y el optimizador.

Después de aplicar un preprocesamiento a las senales se extraen características con la Transformada Discreta Wavelet (DWT) y estas se clasifican con una red neuronal optimizada.

### EEG-RedNeuronal-PSO.ipynb
Red neuronal optimizada una capa oculta

### EEG-RedNeuronal2Capas-PSO.ipynb
Red neuronal optimizada dos capas ocultas

### EEGClasificadores.ipynb
Clasificacion de EEG con diferentes clasificadores

### EEGRedNeuronalGeneral.ipynb
Red neuronal normal sin optimizar, hiperparametros por defecto

### EEGRedNeuronalTrainTest.ipynb
Red neuronal con division de datos en train y test