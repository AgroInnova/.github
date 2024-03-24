### 🖥️AgroInnova🍃
AgroInnova busca transformar la agricultura a través de la innovación, la responsabilidad, la sostenibilidad y la accesibilidad. Brindamos soluciones tecnológicas avanzadas para mejorar la producción de alimentos y el uso eficiente de los recursos. Nos comprometemos con la responsabilidad social, trabajando en colaboración con fundaciones y programas de sostenibilidad para llevar nuestra tecnología a comunidades vulnerables. Buscamos generar un impacto social positivo y mejorar la calidad de vida de las personas.

Nuestro producto y servicio consiste en proporcionar soluciones tecnológicas para el control y monitoreo de sistemas aeropónicos o hidropónicos. Utilizamos una estructura modular personalizable, sensores y algoritmos, infraestructura física y en la nube, para tomar decisiones informadas en tiempo real y reducir costos de operación. Nuestra tecnología es capaz de optimizar la producción de alimentos, mejorar la eficiencia en el uso de recursos y aumentar la rentabilidad de los agricultores. Además, ofreceríamos servicios de mantenimiento y soporte técnico para garantizar el correcto funcionamiento de nuestros sistemas.

AgroInnova está comprometido a apoyar en los cumplimientos de los Objetivos de Desarrollo Sostenible (ODS):
- Fin de la pobreza  y Hambre cero → Volviendo asequible y rentable para el pequeño agricultor la automatización del cultivo.
- Salud y bienestar → Mejorando el perfil nutricional gracias al cultivo de frutas y verduras.
- Industria, innovación e infraestructura → Trayendo la industria 4.0 con IoT al cultivo con trazabilidad y persistencia aprovechando la tecnología Blockchain.
- Producción y consumo responsables → Gestión eficiente del agua, tierra y energía.


## 🖥️AgroInnova-Expliacion Tecnica🍃
![agroInnovaETHLATAM](https://github.com/AgroInnova/.github/assets/105945231/a75750aa-b195-4a36-b446-a2f16e099718)

[Video de Presentacion tecnica del prototipo](https://youtu.be/cYisdLh59l0)

#### Repositorios Relevantes


- [ICP Cannisters](https://github.com/AgroInnova/ICP_frontend_Backend)https://github.com/AgroInnova/ICP_frontend_Backend
+ [Backend Local Web2, NestJS ](https://github.com/AgroInnova/AgroInnova_NestEdge)https://github.com/AgroInnova/AgroInnova_NestEdge
* [MQTT Testers -Python(Simulacion esp32)](https://github.com/AgroInnova/mqtt-testers)https://github.com/AgroInnova/mqtt-testers
- [Contrats & Resolvers EAS](https://github.com/AgroInnova/AgroInnova-SmartContracts-Resolvers)https://github.com/AgroInnova/AgroInnova-SmartContracts-Resolvers


#### Smart Contracts & Resolvers

[ATTESTER
0x4D57CEA19A2783D96872C965E7A092250bbf5775
](https://sepolia.scrollscan.com/address/0x4D57CEA19A2783D96872C965E7A092250bbf5775)https://sepolia.scrollscan.com/address/0x4D57CEA19A2783D96872C965E7A092250bbf5775


[Resolver 
0x56A7c6cF042EabF0DCC109956c226D1743aeA84C
](https://sepolia.scrollscan.com/address/0x56a7c6cf042eabf0dcc109956c226d1743aea84c#code)https://sepolia.scrollscan.com/address/0x56a7c6cf042eabf0dcc109956c226d1743aea84c#code

[SCHEMA:#108
0x14050ed8107691323eb632a934dfc33e1338e7950894a8edb1d3f6fbce0d79fe](https://scroll-sepolia.easscan.org/schema/view/0x14050ed8107691323eb632a934dfc33e1338e7950894a8edb1d3f6fbce0d79fe)https://scroll-sepolia.easscan.org/schema/view/0x14050ed8107691323eb632a934dfc33e1338e7950894a8edb1d3f6fbce0d79fe

[EAS
0xaEF4103A04090071165F78D45D83A0C0782c2B2a](https://sepolia.scrollscan.com/address/0xaEF4103A04090071165F78D45D83A0C0782c2B2a#code)https://sepolia.scrollscan.com/address/0xaEF4103A04090071165F78D45D83A0C0782c2B2a#code

[RECIPIENT
0x1684C2a107C113c4CCB02dF651933978491dB385](https://sepolia.scrollscan.com/address/0x1684C2a107C113c4CCB02dF651933978491dB385)https://sepolia.scrollscan.com/address/0x1684C2a107C113c4CCB02dF651933978491dB385



## 🖥️Prototype demo deployment🍃

To deploy the prototype testing environment you will nedd the following.

If using windows, you'll need wsl, ubuntu as the main os would be the best but having everything in wsl will work as well.

####You will need:
- Python 
- Nodejs19+ 
- DFX(ICP CLI) :[ Here](https://internetcomputer.org/docs/current/developer-docs/developer-tools/dev-tools-overview)https://internetcomputer.org/docs/current/developer-docs/developer-tools/dev-tools-overview
- NestJS : [Here:](https://docs.nestjs.com/)https://docs.nestjs.com/
- Ionic : [Here](https://ionicframework.com/)https://ionicframework.com/ 


#### Clone the following repositories
````
git clone https://github.com/AgroInnova/ICP_frontend_Backend.git
git clone https://github.com/AgroInnova/AgroInnova_NestEdge.git
git clone https://github.com/AgroInnova/mqtt-testers.git
git clone https://github.com/AgroInnova/AgroInnova-SmartContracts-Resolvers.git
````

#### Setup
Once you have DFX CLI, make sure to uprgade it
```
$dfxvm update
```

To ensure you have the latest version Dfx.
```
$ dfx --version
dfx 0.18.0
```

Go into the ICP_frontend_Backend directory.
```
$cd ICP_frontend_Backend
$npm install
$dfx start --host 127.0.0.1:8000 --clean
```

In here you'll need to wait untill the deployment is complete
Once deployed you'll see this in the terminal

````
Deployed canisters.
URLs:
  Frontend canister via browser
    frontend:
      - http://127.0.0.1:8000/?canisterId=bd3sg-teaaa-aaaaa-qaaba-cai
      - http://bd3sg-teaaa-aaaaa-qaaba-cai.localhost:8000/
    internet_identity:
      - http://127.0.0.1:8000/?canisterId=be2us-64aaa-aaaaa-qaabq-cai
      - http://be2us-64aaa-aaaaa-qaabq-cai.localhost:8000/
  Backend canister via Candid interface:
    backend: http://127.0.0.1:8000/?canisterId=br5f7-7uaaa-aaaaa-qaaca-cai&id=bkyz2-fmaaa-aaaaa-qaaaq-cai
    internet_identity: http://127.0.0.1:8000/?canisterId=br5f7-7uaaa-aaaaa-qaaca-cai&id=be2us-64aaa-aaaaa-qaabq-cai
````

Now go ahead and take a look at the generated .env file within the frontend folder

````
code src/Frontend/.env

````
It should look something like this

````
VITE_CANISTER_ORIGIN=http://bkyz2-fmaaa-aaaaa-qaaaq-cai.localhost:8000
VITE_IDENTITY_PROVIDER=http://be2us-64aaa-aaaaa-qaabq-cai.localhost:8000
II_URL=http://be2us-64aaa-aaaaa-qaabq-cai.localhost:8000
````
You'll need the url on VITE_CANISTER_ORIGIN
Now to make sure that the NestJs backend has access to the ICP backend cannister we need to configure our hosts file.
(if this is not done the NestJS backend will not be able to find the url host to push the data to ICP)

Go ahead and do:

````
$ sudo nano /etc/hosts
````

![image](https://github.com/AgroInnova/.github/assets/105945231/5294957e-6f20-43e0-969e-536b3fe662c8)

Add the highlighted line on 127.0.0.1 with the value provided on VITE_CANISTER_ORIGIN


Now go into the AgroInnova_NestEdge directory

````
cd AgroInnova_NestEdge
````

While in there you'll need to add the endpoint mannually, since the cannister url changes on different deployments and systems

````
$code src/typeormsqlite/typeormsqlite.service.ts

````
Youll need to change the endpoint that is on the post with the information on the env variable VITE_CANISTER_ORIGIN/sensorData

![image](https://github.com/AgroInnova/.github/assets/105945231/528128b8-8a69-4a64-b179-e509fb72ca31)



