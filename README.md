PRACTICA2

//Todo el inicio
-
-Añadido public void reset en simulator.java

-Se añade tostring en DefaultR y DynamicR

-Se ha cambiado factor food en dynamic de 1000 a 100

-Se añaden fillIns en Default y Dynamic Builder

//Inicia enunciado en Region Manager
-
-Se rellena RegionInfo(interfaz)

-Se importa el AnimalInfo y se añade el public list<AnimalInfo> en Region.java

-Se añade record en MapInfo.java

-Hacer Importaciones en RegionM.java

-Añadir iterator al final de RegionM.java antes de getters

//Inicia enunciado en EcoSysObserver
-
-Crear Interfaz Observable dentro de sim.model

-Crear Interfaz EcoSysObservable dentro de sim.model

-Actualizar Simulator.java

//Inicia enunciado en Controller
-
-Añadidos los métodos correspondientes para evitar pasar el simulador a la GUI

//Inicia enunciado en Main
-
-Cambiados los atributos de las factorías y delta-time a público para llevar mejor la interfaz (GUI)

//Inicia desarrollo de interfaz de Usuario
-
-Creado el paquete simulator.model.GUI para guardar las clases correspondientes con la interfaz de usuario

(Ventana principal)
-
-Creada clase MainWindow (falta retocarla porque es la última a terminar ya que depende de las otras)

(Barra de Control)
-Creada clase ControlPanel 
-Empieza creando todos los botones (Open, MapWindow, ChangeRegions, Run, Stop, Quit) y componentes de Steps y Delta-time
-Necesitamos que tenga las imágenes mediante los métodos dados (hace falta añadirlas)
-Los botones se supone que tiene ya la lógica integrada en el código que te he dado

(Barra Estado)
-Creada clase StatusBar sin terminar

(TablasInfo)
-Creada clase InfoTable y terminada
-Modifica para que se vea como se pide con BorderLayout, con título y un Jtable con barra de desplazamiento (JScrollPane(table))

(TablaEspecies)
-Creada clase SpeciesTableModel con atributos y el constructor pero sin terminar (no se si hace falta añadir algo mas)

(TablaReg)
-Creada clase RegionsTableModel sin terminar

(DialogoCambioReg)
-Creada la clase ChangeRegionsDialog y terminada (capaz y necesita un repaso)
-Crea varios paneles y organiza los componentes visuales (texto de ayuda, tabla...)
-Obtiene la información de las regiones para sacarlo en la tabla
-Solo se hace editable la parte de los valores (food y factor)
-Crea varios combobox para varios valores (fromRowModel, toRowModel, fromColModel y toColModel…)
-Crea los botones OK y Cancel y realiza la lógica en métodos a parte

(VisorMapa)
-Es necesario hacer cambios en la clase MapViewer (creada en el paquete simulator.view) (Los `TODO`) para que funcione bien antes 

//Cambios en clase main
-

//MetodoStartGUIMODE
-
