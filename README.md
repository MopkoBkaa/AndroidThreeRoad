Не очень разобрался с github(если быть предельно честным - то вовсе не разбирался). Более точное название проекта GeoQuiz - это первое упражненение из книги "Android. Програмирование для профессионалов 4е издание".
В самом ближайшем будущем добавлю обновление этого упражнение - выполнение доп.заданий в конце главы. Код старался сделать максимально приблеженным к коду книги, за исколючением пары строк с текстом для виджетов,
однако в XML верстке main_activity пришлось добавить в первый LinearLayout строку: android:layout_gravity="center"
полный код получился такой:
<LinearLayout android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:orientation="vertical"
    android:gravity="center"
    android:layout_gravity="center"
    xmlns:android="http://schemas.android.com/apk/res/android">

    <TextView...
Сделано это было для того чтобы виджеты были в центре - без этой строки они будут в левом верхнем углу.
За исключением этого - все остальное идентично книги
