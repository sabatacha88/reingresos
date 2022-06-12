# reingresos

El fichero CSV contiene una serie de registros relacionados con ingresos de pacientes en un Hospital que han sido obtenidos por el servicio de codificación.

La variables son las siguientes:

**Servicio_Ingreso:** 

	Es el servicio donde el paciente cursa el ingreso, con caracter provisional o definitivo y en uno de los siguientes:

	Hematología
	Medicina Interna
	Medicina Intensiva
	Nefrología
	Oncología
	Cirugía general
	Digestivo
	Cardiología
	Neumología
	Neurología
	Traumatología
	Cirugía Cardio Vascular
	Urología
	Otorrinolaringología
	Cirugía Maxilofacial
	Psiquiatría
	Reumatología
	Neurocirugía
	Cirugía Toracica
	Cirugía plastica


**Servicio_Alta:**

	Es el servicio donde el paciente cursa el alta, con caracter definitivo el paciente permanecerá en este servicio hasta el alta
	en uno de los siguientes:

	Hematología
	Medicina Intensiva
	Nefrología
	Oncología
	Cirugía general
	Digestivo
	Cardiología
	Neumología
	Neurología
	Cirugía plastica
	Anestesia 
	Cirugía Toracica
	Urología
	Otorrinolaringología
	Cirugía Maxilofacial
	Traumatología
	Obstetricia Ginecología
	Neurocirugía
	Psiquiatría


**Edad:**

	Esta edad que tiene cada paciente en el momento del ingreso


**Codigo_Postal:**

	Es el código postal relaccionado con el lugar de residencia del paciente en el momento del ingreso. 
	Esta información está relaccionada con la zona basica de salud.


**día_estancia_hospital:**

	Días que dura el ingreso hospitalário.


**Fecha_ingreso:**

	Es la fecha y hora registrada del ingreso hospitalario

**Fecha_alta:**

	Es la fecha y Hora registrada del día de alta médica


**CDM_Categorias_Diagnosticas_mayores:**

	Enfermedad Infecciosa y parasitaria
	Enfermedades del aparato digestivo
	Enfermedades del aparato respiratorio
	Enfermedades del sistema nervioso y órganos de los sentidos
	Síntomas, signos, condiciones mal definidas y factores que influyen en el estado de salud
	Neoplasias
	Enfermedades de la sangre y órganos hematopoyéticos
	Lesiónes e intoxicaciones
	Enfermedades endocrinas, nutricionales y metabólicas y trastornos de inmunidad
	Enfermedades Mentales
	Enfermedades del aparato circulatorio
	Códigos residuales, no clasificados y todos los códigos E 259 y 260
	Enfermedades del sistema osteomuscular y tejido conectivo
	Enfermedades de la piel y tejido subcutáneo
	Enfermedades del sistema genitourinario
	Complicaciones del embarazo, parto y puerperio
	Determinadas afecciones que se originan en el período perinatal
	Anomalías Congénitas
	No Codificado


**CIE:**

	CIERTAS ENFERMEDADES INFECCIOSAS Y PARASITARIAS (A00-B99)
	NEOPLASIAS (C00-D49)
	ENFERMEDADES DE LA SANGRE Y ÓRGANOS HEMATOPOYÉTICOS Y CIERTOS TRASTORNOS QUE AFECTAN AL MECANISMO INMUNOLÓGICO (D50-D89)
	ENFERMEDADES ENDOCRINAS, NUTRICIONALES Y METABÓLICAS (E00-E89)
	TRASTORNOS MENTALES, DEL COMPORTAMIENTO Y DEL DESARROLLO NEUROLÓGICO (F01-F99)
	ENFERMEDADES DEL SISTEMA NERVIOSO (G00-G99)
	ENFERMEDADES DEL OJO Y SUS ANEXOS (H00-H59)
	ENFERMEDADES DEL OÍDO Y DE LA APÓFISIS MASTOIDES (H60-H95)
	ENFERMEDADES DEL APARATO CIRCULATORIO (I00-I99)
	ENFERMEDADES DEL APARATO RESPIRATORIO (J00-J99)
	ENFERMEDADES DEL APARATO DIGESTIVO (K00-K95)
	ENFERMEDADES DE LA PIEL Y DEL TEJIDO SUBCUTÁNEO (L00-L99)
	ENFERMEDADES DEL APARATO MUSCULOESQUELÉTICO Y DEL TEJIDO CONECTIVO (M00-M99)
	ENFERMEDADES DEL APARATO GENITOURINARIO (N00-N99)
	EMBARAZO, PARTO Y PUERPERIO (O00-O9A)
	CIERTAS AFECCIONES ORIGINADAS EN EL PERÍODO PERINATAL (P00-P96)
	MALFORMACIONES CONGÉNITAS, DEFORMIDADES Y ANOMALÍAS CROMOSÓMICAS (Q00-Q99)
	SÍNTOMAS, SIGNOS Y RESULTADOS ANORMALES DE PRUEBAS COMPLEMENTARIAS, NO CLASIFICADOS BAJO OTRO CONCEPTO (R00-R99)
	LESIONES TRAUMÁTICAS, ENVENENAMIENTOS Y OTRAS CONSECUENCIAS DE CAUSAS EXTERNAS (S00-T88)
	FACTORES QUE INFLUYEN EN EL ESTADO DE SALUD Y CONTACTO CON LOS SERVICIOS SANITARIOS (Z00-Z99)
	N/D


**DIABETES_MELLITUS:**

	1: NO DM
	2: PreDM
	3: DM 1
	4: DM 2


**ALERGIAS:**

	1: NO
	2: SI

**REACCION_ADVER_A_FARM:**

	Reacción adversa a fármacos
	
	1: NO
	2: SI

**HAB_ENOLICO:**

	Habito enólico
	
	1: NO Consume
	2: Bebedor
	3: Ocasional
	4: Exenólico


**DISLIPEMIA:**

	1: NO
	2: SI

**HABITO_TABAQUICO:**

	1: NO
	2: SI	
	3: EXfum

**HIPERTENSION_ARTE:**

	Hipertensión arterial
	
	1: NO
	2: SI

**TRATAMIENTO_CRONICO:**

	1: NO
	2: SI

**ECOGRAFIA_URGENCIAS:**

	1: NO
	2: SI

**RX:**

	Radiografía urgente
	
	1: NO
	2: SI
	
**NIVEL_TRIAJE:**

	Nivel de triage de clasificación del paciente según gravedad y tipo de atención
	
	1: Nivel 1
	2: Nivel 2
	3: Nivel 3
	4: Nivel 4
	5: Nivel 5

**TAC_URGENCIAS:**

	Le han realizado un TAC urgente
	
	1: NO
	2: SI

**Sexo01:**
	
	0: HOMBRE
	1: MUJER

**reingresos:**

	Es la variable de clase para la predicción de reingreso hospitalario:
	
	0: NO
	1: SI
