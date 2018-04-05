Team Name: 

	Kerbal C++ Program??

Members:

	Tyler Mclain
	Eliot Heinrich
	Luke Beatty

Classes:

	Rocket
	private:
		vector<RocketPart*> parts; (has-a)
	public:
		vector<RocketPart*> getParts();
		void draw(double x, double y, double angle);

	RocketPart (Abstract)
	Methods:
		virtual draw(double x, double y, double angle) = 0;

	CommandModule: RocketPart
	private:
		Mass
		Length
	public:
		getMass
		getLength
		setMass
		setLength

	FuelTank: RocketPart
	private:
		Mass
		Length
	public:
		getMass
		getLength
		setMass
		setLength

	Thruster: RocketPart
	private:
		Mass
		Length
	public:
		getMass
		getLength
		setMass
		setLength
	
	DrawWorld
		//Creates environment
	
	DrawStartScreen
		//Creates start screen
		
	DrawEndScreen
		//Creates end screen

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
	Everyone: Testing
