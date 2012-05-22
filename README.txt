Proyecto para cakePhp 2
Componente conexión api Mailchimp 


pasos de instalación

1.Añadir a los archivos de la carpeta components en app/controller/components de cakePhp.
2.Llamar desde cualquier controllador var $components=array( 'Mailchimp');
3.Crear una función utilizando el componente. (ejemplo listado de listas)
	$this->Mailchimp->MCAPI("API_KEY");
	$list = $this->Mailchimp->lists();