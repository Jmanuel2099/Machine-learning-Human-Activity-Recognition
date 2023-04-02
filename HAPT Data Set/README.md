===================================================================================================
Smartphone-Based Recognition of Human Activities and Postural Transitions Data Set
Version 2.1
===================================================================================================
Jorge L. Reyes-Ortiz(1,2), Davide Anguita(1), Luca Oneto(1) and Xavier Parra(2)
1 - Smartlab, DIBRIS - Universit�  degli Studi di Genova, Genoa (16145), Italy. 
2 - CETpD - Universitat Polit�cnica de Catalunya. Vilanova i la Geltr� (08800), Spain
har '@' smartlab.ws 
www.smartlab.ws
===================================================================================================

The experiments were carried out with a group of 30 volunteers within an age bracket of 19-48 years. They performed a protocol of activities composed of six basic activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs and walking upstairs). The experiment also included postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All the participants were wearing a smartphone (Samsung Galaxy S II) on the waist during the experiment execution. We captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. The experiments were video-recorded to label the data manually. The obtained dataset was randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of 561 features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

This dataset is an extended version of the UCI Human Activity Recognition Using smartphones Dataset that can be found at: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
This version provides the original raw inertial signals from the smartphone sensors, instead of the ones pre-processed into windows which were provided in version 1. This change was done in order to be able to make online tests with the data. Moreover, the activity labels were updated in order to include postural transitions that were not part of the previous version of the dataset. 

The dataset is then divided in two parts and they can be used separately.  

1. Inertial sensor data 
- Raw triaxial signals from the accelerometer and gyroscope of all the trials with with participants. 
- The labels of all the performed activities.
  
2. Records of activity windows. Each one composed of:
- A 561-feature vector with time and frequency domain variables. 
- Its associated activity label. 
- An identifier of the subject who carried out the experiment.


The dataset includes the following files:
=========================================

- 'README.txt'

- 'RawData/acc_expXX_userYY.txt': The raw triaxial acceleration signal for the experiment number XX and associated to the user number YY. Every row is one acceleration sample (three axis) captured at a frequency of 50Hz. 

- 'RawData/gyro_expXX_userYY.txt': The raw triaxial angular speed signal for the experiment number XX and associated to the user number YY. Every row is one angular velocity sample (three axis) captured at a frequency of 50Hz. 

- 'RawData/labels.txt': include all the activity labels available for the dataset (1 per row). 
   Column 1: experiment number ID, 
   Column 2: user number ID, 
   Column 3: activity number ID 
   Column 4: Label start point (in number of signal log samples (recorded at 50Hz))
   Column 5: Label end point (in number of signal log samples)

- 'features_info.txt': Shows information about the variables used on the feature vector.

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the activity ID with their activity name.

- 'Train/X_train.txt': Training set.

- 'Train/y_train.txt': Training labels.

- 'Test/X_test.txt': Test set.

- 'Test/y_test.txt': Test labels.

- 'Train/subject_id_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'Test/subject_id_test.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 


Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the 'X' and 'y' files.
- The units used for the accelerations (total and body) are 'g's (gravity of earth -> 9.80665 m/seg2).
- The gyroscope units are rad/seg.
- A video of the experiment including an example of the 6 recorded activities with one of the participants can be seen in the following link: http://www.youtube.com/watch?v=XOEN9W05_4A

For more information about this dataset please contact har '@' smartlab.ws or check our website www.smartlab.ws


License:
========
Use of this dataset in publications must be acknowledged by referencing the following publications

- Jorge-L. Reyes-Ortiz, Luca Oneto, Albert Sam�, Xavier Parra, Davide Anguita. Transition-Aware Human Activity Recognition Using Smartphones. Neurocomputing. Springer 2015.

This dataset is distributed AS-IS and no responsibility implied or explicit can be addressed to the authors or their institutions for its use or misuse. Any commercial use is prohibited.


Other Related Publications:
===========================

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. 

- Jorge-Luis Reyes-Ortiz, Luca Oneto, Alessandro Ghio, Albert Sam�, Davide Anguita and Xavier Parra. Human Activity Recognition on Smartphones With Awareness of Basic Activities and Postural Transitions. Artificial Neural Networks and Machine Learning � ICANN 2014. Lecture Notes in Computer Science. Springer. 2014.

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra, Jorge L. Reyes-Ortiz. Energy Efficient Smartphone-Based Activity Recognition using Fixed-Point Arithmetic. Journal of Universal Computer Science. Special Issue in Ambient Assisted Living: Home Care.   Volume 19, Issue 9. May 2013

- Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. Human Activity Recognition on Smartphones using a Multiclass Hardware-Friendly Support Vector Machine. 4th International Workshop of Ambient Assited Living, IWAAL 2012, Vitoria-Gasteiz, Spain, December 3-5, 2012. Proceedings. Lecture Notes in Computer Science 2012, pp 216-223. 

- Jorge Luis Reyes-Ortiz, Alessandro Ghio, Xavier Parra-Llanas, Davide Anguita, Joan Cabestany, Andreu Catal�. Human Activity and Motion Disorder Recognition: Towards Smarter Interactive Cognitive Environments. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.  

==================================================================================================
Jorge L. Reyes-Ortiz, Alessandro Ghio, Luca Oneto, Davide Anguita and Xavier Parra. July 2015.


=====================================================================================================
Translate

Los experimentos se llevaron a cabo con un grupo de 30 voluntarios de edades comprendidas entre los 19 y los 48 años. Realizaron un protocolo de actividades compuesto por seis actividades básicas: tres posturas estáticas (de pie, sentado, tumbado) y tres actividades dinámicas (caminar, bajar escaleras y subir escaleras). El experimento también incluía transiciones posturales que se producían entre las posturas estáticas. Estas son: de pie a sentado, de sentado a de pie, de sentado a tumbado, de tumbado a sentado, de tumbado a tumbado y de tumbado a tumbado. Todos los participantes llevaban un smartphone (Samsung Galaxy S II) en la cintura durante la ejecución del experimento. Capturamos la aceleración lineal de 3 ejes y la velocidad angular de 3 ejes a una frecuencia constante de 50 Hz utilizando el acelerómetro y el giroscopio integrados en el dispositivo. Los experimentos se grabaron en vídeo para etiquetar los datos manualmente. El conjunto de datos obtenido se dividió aleatoriamente en dos conjuntos, en los que el 70% de los voluntarios se seleccionó para generar los datos de entrenamiento y el 30% los datos de prueba. 

Las señales de los sensores (acelerómetro y giroscopio) se preprocesaron aplicando filtros de ruido y, a continuación, se muestrearon en ventanas deslizantes de anchura fija de 2,56 segundos y solapamiento del 50% (128 lecturas/ventana). La señal de aceleración del sensor, que tiene componentes gravitatorios y de movimiento del cuerpo, se separó mediante un filtro Butterworth de paso bajo en aceleración del cuerpo y gravedad. Se supone que la fuerza gravitatoria sólo tiene componentes de baja frecuencia, por lo que se utilizó un filtro con una frecuencia de corte de 0,3 Hz. De cada ventana se obtuvo un vector de 561 características calculando variables del dominio del tiempo y de la frecuencia. Para más detalles, véase 'features_info.txt'. 

Este conjunto de datos es una versión ampliada del UCI Human Activity Recognition Using smartphones Dataset que se puede encontrar en: https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+U ing+Smartphones Esta versión proporciona las señales inerciales en bruto originales de los sensores de los smartphones, en lugar de las preprocesadas en ventanas que se proporcionaron en la versión 1. Este cambio se realizó con el fin de obtener las señales inerciales originales de los sensores de los smartphones. Este cambio se realizó para poder realizar pruebas en línea con los datos. Además, se actualizaron las etiquetas de actividad para incluir transiciones posturales que no formaban parte de la versión anterior del conjunto de datos.

A continuación, el conjunto de datos se divide en dos partes que pueden utilizarse por separado.  

1. Datos del sensor inercial 
- Señales triaxiales en bruto del acelerómetro y el giroscopio de todas las pruebas con participantes. 
- Las etiquetas de todas las actividades realizadas.
  
2. Registros de las ventanas de actividad. Cada una compuesta por:
- Un vector de 561 características con variables en el dominio del tiempo y la frecuencia. 
- Su etiqueta de actividad asociada. 
- Un identificador del sujeto que realizó el experimento.

El conjunto de datos incluye los siguientes archivos:
=========================================

- README.txt

- RawData/acc_expXX_userYY.txt': La señal de aceleración triaxial en bruto para el experimento número XX y asociada al usuario número YY. Cada fila es una muestra de aceleración (tres ejes) capturada a una frecuencia de 50 Hz. 

- RawData/gyro_expXX_userYY.txt': La señal de velocidad angular triaxial en bruto para el experimento número XX y asociada al número de usuario YY. Cada fila es una muestra de velocidad angular (tres ejes) capturada a una frecuencia de 50 Hz. 

- 'RawData/labels.txt': incluye todas las etiquetas de actividad disponibles para el conjunto de datos (1 por fila). 
   Columna 1: ID del número de experimento, 
   Columna 2: ID del número de usuario, 
   Columna 3: ID del número de actividad 
   Columna 4: punto de inicio de la etiqueta (en número de muestras del registro de señales (registradas a 50 Hz))
   Columna 5: punto final de la etiqueta (en número de muestras del registro de señales)

- 'features_info.txt': Muestra información sobre las variables utilizadas en el vector de características.

- features.txt Lista de todas las características.

- activity_labels.txt': Vincula el ID de actividad con su nombre de actividad.

- 'Train/X_train.txt': Conjunto de entrenamiento.

- Train/y_train.txt': Etiquetas de entrenamiento.

- Test/X_test.txt': Conjunto de prueba.

- Test/y_test.txt': Etiquetas de prueba.

- Train/subject_id_train.txt': Cada fila identifica al sujeto que realizó la actividad para cada muestra de ventana. Su rango va de 1 a 30. 

- Test/subject_id_test.txt': Cada fila identifica al sujeto que realizó la actividad para cada ventana de muestra. Su rango va de 1 a 30.

Notas: 
======
- Las características están normalizadas y delimitadas dentro de [-1,1].
- Cada vector de características es una fila en los archivos 'X' e 'y'.
- Las unidades utilizadas para las aceleraciones (total y del cuerpo) son 'g's (gravedad de la tierra -> 9.80665 m/seg2).
- Las unidades del giroscopio son rad/seg.
- En el siguiente enlace se puede ver un vídeo del experimento que incluye un ejemplo de las 6 actividades grabadas con uno de los participantes: http://www.youtube.com/watch?v=XOEN9W05_4A

Para más información sobre este conjunto de datos, póngase en contacto con har '@' smartlab.ws o consulte nuestro sitio web www.smartlab.ws.