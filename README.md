
# Tarea3_1028916

## Polimorfismo

# Codigo:

### WaterMonster:

clase pública WaterMonster  implements Monster {
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Agua");
	}
}

### FireMonster: 

clase pública FireMonster  implements Monster {
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Fuego");
	}

}

### StoneMonster:

clase pública StoneMonster  implements Monster {
	
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Piedra");
	}

}

### PolimorfismoMain:

clase pública PolimorfismoMain  implements Monster {
	
	public static void Main (String [] args) {
		Monstruo m ^ {1}, m2, m ^ {3};
		
		m1 = nuevo WaterMonster (); 
		System.out.println (m1.toString ());
		
		m2 = nuevo FireMonster ();
		System.out.println (m2.toString ());
		
		m3 = nuevo StoneMonster (); 
		System.out.println (m3.toString ());
	}

}


### Monster: 

clase interface Monster {
	
	
	Ataque de cuerdas;
	
	public void TipoAtaque () {
		System.out.println ("¿Qué tipo de ataque es?");
	}

}

