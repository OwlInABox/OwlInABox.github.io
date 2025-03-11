Docker Container communication.

sprøgsmål: hvordan får jeg to containers til at kommunikerer sammen?

Process:

inden at jeg kaster mig over brug af enten Docker swarm eller kubernetties, er der nødvendigt
at have en basic forstårelse af hvordan Docker Containers virker med netværk. specielt hvis en container med en services skal tilgås ude fra det lokale netværk.

for at få et indblik i detter har jeg se youtube video af NetworkChuck, "Docker networking is CRAZY!! (you NEED to learn it)"[1]    som gav mig en godt overblik af 7 forskellige netværks opsætninger som der til rådighed for docker, og hvad deres styrker og svaghedder var.

baseret på den video, vurderede jeg det ville være smart at lave lidt øvelse selv, derfor lavede jeg en plan. 

på mit eget lokale net derhjemme med 2 pc'er (stationer og en raspberry pi der tilgås via SSH) 
kunne jeg hurtigt installere docker og lave en nogen test containers der kunne ping hianden.
senere vil det så være en mulighed at oprette en python flask webapp som en udvidelse af uge 7s dockerfile testing. til at udføre disse test, har jeg valgt af bruge et docker image af navn/type "Alpine" som har en meget lille størelse, men har de værktøjer jeg skal bruge og har mulighed for at understøtte en senere opsætning af Flask.

plan ved bestå af 3 faser som vil teste forskellige kommunikation senarier. 

a: test mellem 2 containers på samme host.

b: test mellem host og container

c: test mellem ikke host-pc og container.

hvis det lykkes at komme alle disse test igennem, kan der efterfølgende bruge denne viden til at når en blazor webapp sættes op med api-endpoints

[1] https://www.youtube.com/watch?v=bKFMS5C4CG0 