function carregar() {
	var msg = window.document.getElementById('msg')
	var img = window.document.getElementById('imagem')
	var data = new Date()
	var horagora = data.getHours()
	msg.innerHTML = 'Agora são ${horagora} horas'
	if (horagora >= 0 && horagora < 12) {
		//Bom dia!
	img.src = 'foto1.jpg'
	} else if (horagora >= 12 && horagora <= 18) {
		//Boa Tarde!!
	img.src = 'foto2.jpg'
	} else	{
		//Boa Tarde!!
	img.src = 'foto3.jpg'
	}
}

