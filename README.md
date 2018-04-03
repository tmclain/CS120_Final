# CS120_Final

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

	FuelTank: RocketPart

	Thruster: RocketPart

Things to write to a file to save:

•	Rocket Parts
•	Rocket Location

Keyboard Keys:

