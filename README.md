questa libreria serve per semplificare l'adattamento di un SFC (Sequential Functional Chart) a un linguaggio di programmazione come il c++, per renderlo compatibile con arduino e i suoi pin.
i pin solo limitati da 0 a 19 in caso di utilizzo di arduino mega o altri microcontrollori con più pin
per usare i timer bisogna inserire i pin da 20 a 39, e il tempo in millisecondi sul valore richiesto dalla transizione per essere verificata per poter usufruire di 20 timer
la libreria raggiunge un massimo di 50 stati e di 50 transizioni, non possiede contatori e non si possono effettuare AND tra timer o pin.
