# Ingenieria-de-datos-Cloud.
## Desafio #1 y #2

*#1 Construya un script que genere de forma automática los datos de: departamentos, puestos de trabajo, y empleados.* 

*#2 Guarde los datos simulados en archivos con formato CSV/Parquet. Explique el porqué de la escogencia del formato. No descarte usar la capa gratuita de algún servicio de almacenamiento tipo cloud, será considerado un plus.*

**Creando Bucket S3:**
![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/673247e2-ccab-497f-8849-684eb4f2b46f)
**Creando un Bloc de notas con SageMaker:**

- Vamos a [Amazon SageMaker](https://us-east-1.console.aws.amazon.com/sagemaker/home?region=us-east-1#/landing)/Instancias de bloc de notas y seguimos los pasos:
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/a4a5f621-e385-4749-8841-4afbaa221384)
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/6cee2474-39e0-400a-a1a9-25bbcfea6c18)
- Creamos un rol con acceso a **AWS S3**
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/b50cc08a-5638-48b8-ba1d-c144d4428fd4)
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/47807da8-fdd8-4a4c-b174-779f3757a56e)
- Repositorio Git del Desafio #1 y #2:
  ```
  https://github.com/1treu1/Ingenieria-de-datos-Cloud.git
  ```
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/e8253cc7-b04a-454a-b4e9-16d92cff1fc7)
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/c7a063a3-d2e9-470b-b622-188d0847a630)
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/83c4aebc-1188-46bb-970d-353ca3b75cbd)
 - Abrir y ejecutar **Desafio_1_y_2.ipynb**
  ![image](https://github.com/1treu1/Ingenieria-de-datos-Cloud/assets/71142778/2a76dc6c-5df8-4097-a36e-edea2f0453a7)
**Notas:**

- Para este desafio se usó la libreria Faker que permite generar cantidades masivas de datos falsos (pero realistas) para pruebas y desarrollo.
- Tambien se creo una lista con los departamentos de Colombia y con algunos trabajos.
- Se usó un archivo Parquet ya que estos son binarios y están optimizados para análisis y procesamiento eficiente. Debido a su compresión y codificación de columnas, pueden proporcionar un rendimiento más rápido para consultas y análisis. Por otro lado los archivos .csv son archivos de texto plano y generalmente ocupan más espacio en disco en comparación con Parquet. Para grandes volúmenes de datos, esto puede afectar negativamente el rendimiento de las consultas y análisis.

Documentación detallada: https://axiomatic-ticket-4ff.notion.site/PRUEBA-T-CNICA-INGENIERIA-DE-DATOS-ClOUD-LABS-c0c66396f7764631bb307487a12a13d5?pvs=4






