# Hiding-StatusBar
Metodo para esconder el estatus bar de una actividad

##Ejemplo
Este fragmento de codigo permite esconder el Status bar dentro de una actividad
```java
View decorView = getWindow().getDecorView();
int uiOptions = View.SYSTEM_UI_FLAG_FULLSCREEN;
decorView.setSystemUiVisibility(uiOptions);
```
