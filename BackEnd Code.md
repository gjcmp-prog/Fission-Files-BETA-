#include <iostream>
#include <stdlib.h>


using namespace std;

string username;
string HackerPW = "$cr!pt";
string PorkPW = "Squishy01";
string MonkeyPW = "Banana04";


// Gabriel's Hack Codes
string hack_code101 = "*101#";
string hack_code102 = "*102#";
string hack_code103 = "*103#";

string bomb_files_code = "31143";

//*** Logins ***
	// Cyb3rHack3r = Gabriel
	// P0rk = Jack
	// M0nK3y = Marvin


//All user Integers
int Home_DB_choice;

//Marvin Integers
int PODServ_choice;

//Gabriel Integers
int POD_DB_choiceA;
int POD_DB_choiceB;

string Jack_Role = "A.N.T.P Missile Design Engineer.";
string Marvin_Role = "A.N.T.P Cyber Security Technichian.";
string Gabriel_Role = "A.N.T.P Sr. BackEnd Hacking Engineer";



int main() {

	cout << "\n\n \t\t\t\t\t\t\t\t *** Initiating Fission Database ***";
	cin.get();
	cout << "\n\n Please Wait...";
	system("cls");
	cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION FILES DATABASE ---";
	cout << "\n\n USERNAME: ";
	cin >> username;
	cin.get();
	system("cls");


	//Jack's user options 

	if (username == "P0rk")
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION FILES DATABASE ---";
		cout << "\n\n Pork's PASSWORD:  ";
		cin >> PorkPW;
		cin.get();
		system("cls");
	}

	if (username == "P0rk" && PorkPW == "Squishy01")
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
		cout << "\n\n Greetings Jack,  ";
		cout << Jack_Role;
		cout << "\n\n\n\n Select from the following Options to begin:";
		cout << "\n\n 1. Fission Story";
		cout << "\n\n 2. Bomb Files";
		cout << "\n\n 3. Messages from President Eisenhower (CONFIDENTIAL)";

		cout << "\n\n 0. Exit Terminal";

		cout << "\n\n\n Hit ENTER to input selection...";

		cin.get();
		system("cls");
		cout << "\n\n Goto: ";
		cin >> Home_DB_choice;
		system("cls");

		if (Home_DB_choice == 1)
		{
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY --- \n\n";
			cin.get();
			cout << "\n\n In 1954, President Dwight D. Esienhower approved the commencement of Project A.N.T.P (American Nuclear Test Projectiles).";
			cin.get();
			cout << "\n\n A.N.T.P, was developed to protect the United States of America from threats of nuclear war posed by the USSR.";
			cin.get();
			cout << "\n\n The program created an entire underground dwlleling for miltary persons to survive a nuclear war.";
			cin.get();
			cout << "\n\n The hope was to preserve humankind and allow survivors to rebuild America after the fallout.";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
			cout << "\n\n The US drafted any and all willing humans residing in the States, male, female, and other,";
			cin.get();
			cout << "\n\n to occupy the goverment funded underground chamber storge units for 10 years in an effort to test the units' effectiveness.";
			cin.get();
			cout << "\n\n On Christmas day, 1955, Soviet Union leader Nikita Krushcev, launched the USSR's first test nuclear bomb with Lady Liberty in New York, NY, USA as its target.";
			cin.get();
			cout << "\n\n Krushcev's action resulted in Esienhower decalring nuclear war on the USSR, thus resulting in NWWI (Nuclear World War 1).";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
			cout << "\n\n The war destroyed 95.8% of human kind and they remaining 4.2% mutated into zombies.";
			cin.get();
			cout << "\n\n The occupants of Chamber 47 were left to rebuild and repopulate a post-war Washing D.C. and the greater United States of America.";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
			cout << "\n\n Greetings Jack,  ";
			cout << Jack_Role;
			cout << "\n\n Select from the following Options to begin:";
			cout << "\n\n 1. Fission Story";
			cout << "\n\n 2. Bomb Files";
			cout << "\n\n 3. Messages from President Eisenhower (CONFIDENTIAL)";

			cout << "\n\n 0. Exit Terminal";

			cout << "\n\n\n Hit ENTER to input selection...";

			cin.get();
			system("cls");
			cout << "\n\n Goto: ";
			cin >> Home_DB_choice;
			system("cls");
		}
		if (Home_DB_choice == 2)
		{
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- BOMB FILES --- \n\n";
			cin.get();
			cout << "\n\n Enter Access Code: ";
			cin >> bomb_files_code;
			cin.get();
			system("cls");

			if (bomb_files_code == "31143")
			{
				cout << "\n\n \t\t\t\t\t\t\t\t\t *** THE PATRIOT (Description) *** \n\n";
				cin.get();
				cout << "\n\n THE PATRIOT is America's first defense against nuclear threats and serves as the country's entry into nuclear territory.";
				cin.get();
				cout << "\n\n Originally blueprinted by Dr. Martin Helsinki in 1949, this projectile was designed with performance in mind.";
				cin.get();
				cout << "\n\n Eisenhower specially requested the development of this missle in order to show the USSR that America is not afraid of Nuclear War.";
				cin.get();
				system("cls");

				cout << "\n\n \t\t\t\t\t\t\t\t\t *** THE PATRIOT (Specifications) *** \n\n";
				cin.get();
				cout << "\n\n The outer hull of THE PATRIOT is constructed from pure aluminum in order to maximze performance.";


			}
			else {
				cout << "\n\n \t\t\t\t\t\t\t\t\t ACCESS DENIED";
				cin.get();
				cout << "\n\n Invalid Access Code.";
				cin.get();
				cout << "\n\n Terminating program...";
				exit(0);
			}
		}
	}


	// Marvin Login Options

	if (username == "M0nK3y")
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION FILES DATABASE ---";
		cout << "\n\n Monkey's PASSWORD:  ";
		cin >> MonkeyPW;
		cin.get();
		system("cls");
	}

	if (username == "M0nK3y" && MonkeyPW == "Banana04")
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
		cout << "\n\n Greetings, Marvin,  ";
		cout << Marvin_Role;
		cout << " . \n\n";
		cout << "\n\n\n\n Select from the following Options to begin:";
		cout << "\n\n 1. Fission Story";
		cout << "\n\n 2. Pod Surveillance";
		cout << "\n\n 3. Pod Locks";
		cout << "\n\n 4. Chamber Vacancies";

		cout << "\n\n 0. Exit Terminal";

		cout << "\n\n\n Hit ENTER to input selection...";

		cin.get();
		system("cls");
		cout << "\n\n Goto: ";
		cin >> Home_DB_choice;
		cin.get();
		system("cls");
	}
	if (Home_DB_choice == 1)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY --- \n\n";
		cin.get();
		cout << "\n\n In 1954, President Dwight D. Esienhower approved the commencement of Project A.N.T.P (American Nuclear Test Projectiles).";
		cin.get();
		cout << "\n\n A.N.T.P, was developed to protect the United States of America from threats of nuclear war posed by the USSR.";
		cin.get();
		cout << "\n\n The program created an entire underground dwlleling for miltary persons to survive a nuclear war.";
		cin.get();
		cout << "\n\n The hope was to preserve humankind and allow survivors to rebuild America after the fallout.";
		cin.get();
		system("cls");

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
		cout << "\n\n The US drafted any and all willing humans residing in the States, male, female, and other,";
		cin.get();
		cout << "\n\n to occupy the goverment funded underground chamber storge units for 10 years in an effort to test the units' effectiveness.";
		cin.get();
		cout << "\n\n On Christmas day, 1955, Soviet Union leader Nikita Krushcev, launched the USSR's first test nuclear bomb with Lady Liberty in New York, NY, USA as its target.";
		cin.get();
		cout << "\n\n Krushcev's action resulted in Esienhower decalring nuclear war on the USSR, thus resulting in NWWI (Nuclear World War 1).";
		cin.get();
		system("cls");

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
		cout << "\n\n The war destroyed 95.8% of human kind and they remaining 4.2% mutated into zombies.";
		cin.get();
		cout << "\n\n The occupants of Chamber 47 were left to rebuild and repopulate a post-war Washing D.C. and the greater United States of America.";
		cin.get();
		system("cls");

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
		cout << "\n\n Greetings, Marvin,  ";
		cout << Marvin_Role;
		cout << " . \n\n";
		cout << "\n\n Select from the following Options to begin:";
		cout << "\n\n 1. Fission Story";
		cout << "\n\n 2. Pod Surveillance";
		cout << "\n\n 3. Pod Locks";
		cout << "\n\n 4. Chamber Vacancies";

		cout << "\n\n 0. Exit Terminal";

		cout << "\n\n\n Hit ENTER to input selection...";


		cin.get();
		system("cls");
		cout << "\n\n Goto: ";
		cin >> Home_DB_choice;
		cin.get();
		system("cls");

	}
	if (Home_DB_choice == 2)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE --- \n\n";
		cout << "\n\n Marvin, choose a date to pull POD video camera survaliance logs.";
		cout << "\n\n 1. Date: 6/25/50 -- Start of Korean War ";
		cout << "\n\n 2. Date: 12/25/50 -- Christmas Day '50 (CLASSIFIED)";
		cout << "\n\n 3. Date: 11/22/51 -- Thanksgiving Day '51";
		cout << "\n\n 4. Date: 2/6/52 -- King George VI died";
		cout << "\n\n 5. Date: 1/21/54 -- First Atomic Subarine Launch";

		cout << "\n\n 0. Exit Terminal";

		cout << "\n\n\n Hit ENTER to input selection...";

		cin.get();
		system("cls");
		cout << "\n\n Goto: ";
		cin >> PODServ_choice;
		system("cls");
	}
	if (PODServ_choice == 1)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: June 25th, 1950 --- \n\n";

	}
	if (PODServ_choice == 2)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: December 25th, 1950 (Page 1) --- \n\n";
		cout << "\n\n ***Survaliance Log 3145680:";
		cin.get();
		cout << "\n\n Christmas Day 1950 at 0600 PST the residents of POD 102, a family of three, mysteriously vanished.";
		cin.get();
		cout << "\n\n Survaliance audio captured sounds of the female, one Melissa Frank, crying hysterically and";
		cout << "\n\n uttering the words of an undecipherable foriegn language around midnight the same day.";
		cin.get();
		system("cls");

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: December 25th, 1950 (Page 2) --- \n\n";
		cout << "\n\n ***Survaliance Log 3145680:";
		cin.get();
		cout << "\n\n Occupants of PODs 101 and 103 report sounds of demonic voices and Mrs. Frank shouting blasphemy against Jesus Christ.";
		cin.get();
		cout << "\n\n Investigation into the matter has revealed that every file and record on the Frank family, hard and digital alike,";
		cout << "\n\n have been completely disappeared without a trace. The Eisenhower Administration have been notified. Awaiting follow up.";
		cin.get();
		system("cls");

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- SECURITY TERMINATION --- \n\n";
		cout << "\n\n Terminating database session as per security protocol...";
		cin.get();
		system("cls");

		cout << "\n\n\n\n \t\t\t\t\t\t\t\t\t --- GOODBYE --- \n\n";
		exit(0);

	}
	if (PODServ_choice == 3)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: November 22nd, 1951 --- \n\n";
	}
	if (PODServ_choice == 4)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: February 6th, 1952 --- \n\n";
	}
	if (PODServ_choice == 5)
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD SURVALIANCE: January 21st, 1954 --- \n\n";
	}



	// Gabriel's Login Options

	if (username == "Cyb3rHack3r")
	{

		cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION FILES DATABASE ---";
		cout << "\n\n Cyber Hacker's PASSWORD:  ";
		cin >> HackerPW;
		cin.get();
		system("cls");

	}

	if (username == "Cyb3rHack3r" && HackerPW == "$cr!pt")
	{
		cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
		cout << "\n\n Greetings, Gabriel,  ";
		cout << Gabriel_Role;
		cout << " . \n\n";
		cout << "\n\n\n\n Select from the following Options to begin:";
		cout << "\n\n 1. Fission Story";
		cout << "\n\n 2. Chamber 47 Occupants";
		cout << "\n\n 3. Weapons: assign. & config.";
		cout << "\n\n 4. Turrent Protocols";

		cout << "\n\n 0. Exit Terminal";

		cout << "\n\n\n Hit ENTER to input selection...";

		cin.get();
		system("cls");
		cout << "\n\n Goto: ";
		cin >> Home_DB_choice;
		system("cls");

		if (Home_DB_choice == 1)
		{
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY --- \n\n";
			cin.get();
			cout << "\n\n In 1954, President Dwight D. Esienhower approved the commencement of Project A.N.T.P (American Nuclear Test Projectiles).";
			cin.get();
			cout << "\n\n A.N.T.P, was developed to protect the United States of America from threats of nuclear war posed by the USSR.";
			cin.get();
			cout << "\n\n The program created an entire underground dwlleling for miltary persons to survive a nuclear war.";
			cin.get();
			cout << "\n\n The hope was to preserve humankind and allow survivors to rebuild America after the fallout.";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
			cout << "\n\n The US drafted any and all willing humans residing in the States, male, female, and other,";
			cin.get();
			cout << "\n\n to occupy the goverment funded underground chamber storge units for 10 years in an effort to test the units' effectiveness.";
			cin.get();
			cout << "\n\n On Christmas day, 1955, Soviet Union leader Nikita Krushcev, launched the USSR's first test nuclear bomb with Lady Liberty in New York, NY, USA as its target.";
			cin.get();
			cout << "\n\n Krushcev's action resulted in Esienhower decalring nuclear war on the USSR, thus resulting in NWWI (Nuclear World War 1).";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- FISSION STORY (Cont.)--- \n\n";
			cout << "\n\n The war destroyed 95.8% of human kind and they remaining 4.2% mutated into zombies.";
			cin.get();
			cout << "\n\n The occupants of Chamber 47 were left to rebuild and repopulate a post-war Washing D.C. and the greater United States of America.";
			cin.get();
			system("cls");

			cout << "\n\n \t\t\t\t\t\t\t\t\t --- WELCOME TO THE FISSION FILES DATABASE ---";
			cout << "\n\n Greetings, Gabriel,  ";
			cout << Gabriel_Role;
			cout << " . \n\n";
			cout << "\n\n Select from the following Options to begin:";
			cout << "\n\n 1. Fission Story";
			cout << "\n\n 2. Chamber 47 Occupants";
			cout << "\n\n 3. Weapons Files";
			cout << "\n\n 4. Chamber Vacancies";

			cout << "\n\n 0. Exit Terminal";

			cout << "\n\n\n Hit ENTER to input selection...";

			cin.get();
			system("cls");
			cout << "\n\n Goto: ";
			cin >> Home_DB_choice;
			system("cls");

		}

		if (Home_DB_choice == 2)
		{
			cin.get();
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- CHAMBER 47 --- \n\n";
			cout << "\n\n Select a pod from which to pull occuponant data:";
			cout << "\n\n 1. Pod 101";
			cout << "\n\n 2. Pod 201";
			cout << "\n\n 3. Pod 301";

			cout << "\n\n\n Hit ENTER to input selection...";

			cin.get();
			system("cls");
			cout << "\n\n Goto: ";
			cin >> POD_DB_choiceA;
			system("cls");
		}

		if (POD_DB_choiceA == 1)
		{
			cin.get();
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 101: H@CK --- \n\n";
			cout << "\n\n Enter Hacker's Access Code: ";
			cin >> hack_code101;
			cin.get();
			system("cls");

			if (hack_code101 == "*101#")
			{
				cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 101 --- \n\n";
				cout << "\n\n Select an Occupant: ";
				cout << "\n\n 1. Bradley R. Smith";
				cout << "\n\n 2. Sally J. Smith";
				cout << "\n\n 3. Tommy P. Smith";
				cout << "\n\n\n 0. Home";

				cout << "\n\n\n Hit ENTER to input selection...";

				cin.get();
				system("cls");
				cout << "\n\n Goto: ";
				cin >> POD_DB_choiceB;
				system("cls");
			}
		}
		if (POD_DB_choiceA == 2)
		{
			cin.get();
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 102: H@CK --- \n\n";
			cout << "\n\n Enter Hacker's Access Code: ";
			cin >> hack_code102;
			cin.get();
			system("cls");

			if (hack_code102 == "*102#")
			{
				cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 102 --- \n\n";
				cout << "\n\n Select an Occupant: ";
				cout << "\n\n 1. James L. Felt";
				cout << "\n\n 2. Rebecca A. Felt";
				cout << "\n\n\n 0. Home";

				cout << "\n\n\n Hit ENTER to input selection...";

				cin.get();
				system("cls");
				cout << "\n\n Goto: ";
				cin >> POD_DB_choiceB;
				system("cls");
			}
		}

		if (POD_DB_choiceA == 3)
		{
			cin.get();
			cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 103: H@CK --- \n\n";
			cout << "\n\n Enter Hacker's Access Code: ";
			cin >> hack_code103;
			cin.get();
			system("cls");

			if (hack_code103 == "*103#")
			{
				cout << "\n\n \t\t\t\t\t\t\t\t\t --- POD 103 --- \n\n";
				cout << "\n\n Select an Occupant: ";
				cout << "\n\n 1. Limez A. Couture";
				cout << "\n\n\n 0. Home";

				cout << "\n\n\n Hit ENTER to input selection...";

				cin.get();
				system("cls");
				cout << "\n\n Goto: ";
				cin >> POD_DB_choiceB;
				system("cls");
			}


		}



















	}


	system("pause>0");

	return 0;
}
