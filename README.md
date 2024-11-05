Visualisation of Time series using TimeScaleDB and ApacheSuperset

How to Run the project / Kako pokrenuti projekat	
	
1.Clone the repository  / Klonirajte repozitorijum 

git clone 

2.Install TimeScaleDB (version 16 used in this project) and add the database exactly as specified on the official site: https://docs.timescale.com/self-hosted/latest/install/installation-windows/
/Instalirajte TimeScaleDB (koriscena verzija 16 na ovom projektu) i dodajte bazu podataka na identican nacin kao sto je navedeno na zvanicnom sajtu https://docs.timescale.com/self-hosted/latest/install/installation-windows/ prevedi ovo na engleski

3.Install Docker Desktop (in case it is not already installed on your device)./Instalirajte Docker Desktop(u slucaju da ga nemate instaliranog na uredjaju)

4.Open Docker Desktop, navigate to the superset folder where the docker-compose.yml file is located, then open the command line and start Apache Superset using the command docker-compose up./Otvorite Docker Desktop,pozicionirajte se u superset folder gde se nalazi docker-compose.yml, zatim otvorite komandnu liniju i komandom docker-compose up pokrenite ApacheSuperset

5.Access the admin account in Superset initially with the username admin and password admin./Pristup administratorskom nalogu u Supersetu na pocetku se izvrsava preko username admin i password-a admin	

6.Connect the TimeScale database to Superset using the SQLAlchemy URI./Povezivanje TimeScale baze sa Supersetom preko SQLAlchemi URI-a
