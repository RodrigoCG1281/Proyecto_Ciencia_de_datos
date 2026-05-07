# Proyecto_Ciencia_de_datos
# 📊 Análisis de Ciberdelincuencia en el Perú (Ministerio Público)

## 📝 Descripción del Proyecto
Este repositorio contiene el desarrollo de nuestro proyecto de Ciencia de Datos enfocado en el análisis de los **Delitos por Ciberdelincuencia denunciados en el Ministerio Público del Perú**. 

El objetivo principal de este proyecto es analizar y extraer *insights* sobre la incidencia de delitos informáticos a nivel nacional, evaluando su evolución temporal, distribución por distritos fiscales y la prevalencia de delitos específicos bajo la Ley de Delitos Informáticos (Ley N° 30096).

## 👥 Equipo de Trabajo
* **Condori Gutierrez Rodrigo Bernardo** 
* **Vilca Quispe Oscar Edy**

## 📂 Sobre el Dataset
Los datos utilizados en este proyecto provienen de la Plataforma Nacional de Datos Abiertos del gobierno peruano.

| Atributo | Detalle |
| :--- | :--- |
| **Título** | Delitos por Ciberdelincuencia denunciados en el Ministerio Público |
| **Descripción** | Información de cantidad de delitos denunciados por la Ley N° 30096, a nivel nacional por año, distrito fiscal, delito genérico, subgenérico y artículo de la Ley. |
| **Entidad** | Ministerio Publico Fiscalía de la Nación - [MPFN] |
| **Fuente** | Oficina de Racionalización y Estadística – ORACE |
| **Cobertura Geográfica**| Perú |
| **Formato** | CSV |
| **Frecuencia de Actualización** | Mensual |
| **Versión** | 1.0 (Creado el 31-03-2026) |
| **Licencia** | Open Data Commons Attribution License |
| **Enlace de Descarga** | [Ver en Datos Abiertos](https://www.datosabiertos.gob.pe/dataset/mpfn-delitos-de-ciberdelincuencia-denunciados-en-el-ministerio-p%C3%BAblico) |
| **Contacto** | estadistica@mpfn.gob.pe |

# Diccionario de Datos

## Nombre del Dataset

**DELITOS DENUNCIADOS POR CIBERDELINCUENCIA**

| Variable          | Descripción del Campo                                                                                      | Tipo de Datos | Tamaño | Recurso Relacionado | Información Adicional |
| ----------------- | ---------------------------------------------------------------------------------------------------------- | ------------- | ------ | ------------------- | --------------------- |
| periodo_denuncia  | Meses en que se realizó la denuncia del delito en el Ministerio Público                                    | Texto         | 50     | -                   | -                     |
| año_denuncia      | Año de la denuncia del delito en el Ministerio Público                                                     | Numérico      | 4      | -                   | -                     |
| fecha_descarga    | Fecha de descarga de la información en los sistemas informáticos                                           | Fecha         | -      | -                   | Formato: dd/mm/aaaa   |
| distrito_fiscal   | Nombre del distrito fiscal donde fue registrada la denuncia                                                | Texto         | 30     | -                   | -                     |
| especialidad      | Tipo de especialidad (Penal)                                                                               | Texto         | 10     | -                   | -                     |
| tipo_caso         | Tipo de caso (Denuncia)                                                                                    | Texto         | 10     | -                   | -                     |
| generico          | Delito genérico                                                                                            | Texto         | 100    | -                   | -                     |
| subgenerico       | Delito subgenérico                                                                                         | Texto         | 100    | -                   | -                     |
| articulo          | Artículo del delito según la Ley                                                                           | Alfanumérico  | 10     | -                   | -                     |
| des_articulo      | Nombre o descripción del artículo                                                                          | Texto         | 100    | -                   | -                     |
| cantidad          | Número de delitos denunciados                                                                              | Numérico      | 6      | -                   | -                     |
| ubigeo_pjfs       | Ubigeo de la Presidencia de Junta de Fiscales Superiores del Distrito Fiscal                               | Alfanumérico  | 6      | Catálogo del INEI   | -                     |
| dpto_pjfs         | Departamento donde se encuentra ubicada la Presidencia de Junta de Fiscales Superiores del Distrito Fiscal | Texto         | 70     | Catálogo del INEI   | -                     |
| prov_pjfs         | Provincia donde se encuentra ubicada la Presidencia de Junta de Fiscales Superiores del Distrito Fiscal    | Texto         | 70     | Catálogo del INEI   | -                     |
| dist_pjfs         | Distrito donde se encuentra ubicada la Presidencia de Junta de Fiscales Superiores del Distrito Fiscal     | Texto         | 70     | Catálogo del INEI   | -                     |
| fecha_publicacion | Fecha en que se publica la información en el dataset                                                       | Fecha         | -      | -                   | Formato: dd/mm/aaaa   |

---

## Observaciones

* Los campos de fecha utilizan el formato `dd/mm/aaaa`.
* La información geográfica está basada en el catálogo oficial del INEI.
* El dataset contiene registros de delitos denunciados relacionados con ciberdelincuencia.
