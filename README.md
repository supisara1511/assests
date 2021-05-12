// syles.scss
@im

$themes: ();
$themeValues: ();

@include generateThemeMappings(venio-light, venio-light-theme.$theme);
@include generateThemeMappings(salesbear-light, venio-light-theme.$theme);
html { @include generateThemeVariables;}