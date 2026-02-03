posi();
Scr_movimentacao();
// === Movimento e animação do sapo ===
show_debug_message(vel)
//trocar sprite
switch (estado) {
	case Estados.Parado:
		sprite_index = Spr_parado;
	break;
	case Estados.Parado_back:
		sprite_index = Spr_parado_costas;
	break;
	case Estados.And_front:
	    sprite_index = Spr_caminhando_baixo;
	break;
	case Estados.And_lad_dir:
		sprite_index = Spr_caminhando_direita;
		image_xscale = 1; // garante que fica virado pra direita
	break;
	case Estados.And_lad_esq:
		sprite_index = Spr_caminhando_direita;
		image_xscale = -1; // garante que fica virado pra direita
	break;
	case Estados.And_back:
		sprite_index = Spr_caminhando_cima;
	break;
	case Estados.Qz_and_dir:
		sprite_index = Spr_qz_and;
	break;
		case Estados.Qz_and_esq:
		sprite_index = Spr_qz_and;
		image_index = -1;
	break;
}

if (vel > Vel_max) {
	vel = Vel_max
}
