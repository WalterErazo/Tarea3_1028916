
# Tarea3_1028916

## Polimorfismo

# Codigo:

### WaterMonster:

clase pública WaterMonster extiende Monster {
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Agua");
	}
}

### FireMonster: 

clase pública FireMonster extiende Monster {
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Fuego");
	}

}

### StoneMonster:

clase pública StoneMonster extiende Monster {
	
	
	public void TipoAtaque () {
		System.out.println ("Mi tipo de ataque es Piedra");
	}

}

### PolimorfismoMain:

clase pública PolimorfismoMain {
	
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

clase pública Monster {
	
	
	Ataque de cuerdas;
	
	public void TipoAtaque () {
		System.out.println ("¿Qué tipo de ataque es?");
	}

}

