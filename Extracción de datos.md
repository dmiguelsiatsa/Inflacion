# **Extracción de datos.**

Se usará una técnica de extraer datos estructurados para recopilar el catálogo de productos de diversas cadenas de supermercados.

### **Análisis del sitio web**

El objetivo es crear un fichero .csv de todos los productos con la estructura «Nombre de producto, Precio».


<p class="text_text__1DYNl" data-testid="product-name"> Nombre producto </p>
<p class="text_text__1DYNl text_inline__2pX2N text_nold__1nsB7" data-testid="price"> precio producto </p>


Algunos supermercados son más fáciles de entrar para Scraping que otros:

Fácil entrada:

 * [COSTCO](https://www.costco.com.mx/)
 * [Chedraui](https://www.chedraui.com.mx/)
 * [SAMS Club](https://www.sams.com.mx/)
 * [Waldos](https://waldos.com.mx/)
 * [La Castellana](https://lacastellana.com/#)
 * [Vinoteca](https://www.vinoteca.com/#)
 * [La Europea](https://www.laeuropea.com.mx/)
 * [Bodegas Alianza](https://www.bodegasalianza.com/)
 * [Scorpion](https://www.scorpion.com.mx/)


Difícil entrada:
 * [WALTMART](https://www.walmart.com.mx/)
 * [La Comer](https://www.lacomer.com.mx/lacomer/#!/home?succId=287&succFmt=100)
 * [PRISSA](https://prissa.mx/)
 * [Bodega Aurrera](https://www.bodegaaurrera.com.mx/inicio)
 * [Soriana](https://superentucasa.soriana.com/default.aspx?P=13187)
 * [Fresko](https://www.lacomer.com.mx/lacomer/?_ga=2.21022847.558790867.1627325155-786350580.1627325155#!/home?succId=137&succFmt=100)


No es posible hacerlo:
 * [OXXO](https://www.oxxo.com/)
 * [Go Mart](http://gomart.com.mx/)
 * [Piticó](https://pitico.mx/)
 * [DEl Río](http://delriosa.com/)
 * [El Puma Abarrotero](https://www.elpumaabarrotero.com/)
 * [Zorro Abarrotero](https://zorroabarrotero.com.mx/) (Sólo muestra promociones y descuentos, no muestra precios reales)
 * [7-Eleven](https://www.7-eleven.com.mx/) (Sólo maneja imágenes)
 * [City Market](https://www.citymarket.com.mx/comprasbiencitymarket/)(No maneja precios en su página.)
 * [Tiendas 3B](https://tiendas3b.com/) (Maneja sólo imágenes)
 * [Merza](https://www.merza.com.mx/) (Maneja sólo imágenes)
 * [Garis](https://www.garis.com.mx/home/admin/home.do) (Maneja sólo imágenes)
 * [Kiosco](https://www.mikiosko.mx/web/index.php) (Maneja sólo imágenes)
 * [Circle K](https://www.circlek.com.mx/) (No tiene gran variedad d eproductos.)

No tiene página oficial:
 * SUMESA
 * SuperISSSTE


FUENTE https://www.tiendeo.mx/Tiendas/san-francisco-coacalco/city-market
