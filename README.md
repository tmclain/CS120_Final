Team Name: 

	Rocketmen

Members:

	Tyler Mclain
	Eliot Heinrich
	Luke Beatty
	Evan Fisher

Classes:

	struct Position

	Rocket
	private:
		vector<RocketPart*> parts; (has-a)
		Position p;
		double thrust;
	public:
		Position getPosition() const;
		double getThrust() const;
		setPosition();
		setThrust();
		vector<RocketPart*> getParts();
		void draw(double x, double y, double angle);

	RocketPart (Abstract)
	private:
		double Mass;
		double Length;
	public:
		double getMass() const;
		double getLength() const;
		void setMass();
		void setLength();
		virtual draw(double x, double y, double angle) = 0;

	CommandModule: RocketPart
	private:
		double drag;
		double responsiveness;
	public:
		double getDrag() const;
		double getResponsiveness() const;
		void setDrag();
		void setResponsiveness();
	
	FuelTank: RocketPart
	private:
		double fuel;
	public:
		double getFuel() const;
		void setFuel();

	Thruster: RocketPart
	private:
		double thrust;
	public:
		double getThrust() const;
		void setThrust();
	
	DrawWorld
		//Creates environment
	
	DrawStartScreen
		//Creates start screen
		
	DrawEndScreen
		//Creates end screen
	
	SaveWorld
		//Saves necessary data
	
	LoadWorld
		//Loads necessary data

Things to write to a file to save:

	Rocket Parts
	Rocket Location
	Motion

Keyboard/Mouse Input:

	Keyboard: Thrusters, Steering
	Mouse: Rocket assembly, Main Menu

Core Functionality:

	Five classes listed above
	Visuals of the rocket and planets to land on
	File save method

Extras:

	Visuals – stars, other planets, etc.
	Extra rocket parts

Meeting times:

	Meet in class, use email to communicate primarily.
	Tyler: Mechanics of flight
	Eliot: Rocket Building
	Luke: Environment, Main Menu
	Evan: Undetermined
	Everyone: Testing
