class Fighters{
    public string name;
    public string description;
    public string ability;
    public string fightersName[] = { "X", "Y", "Z"}
    public string fightersDescription[] = { "X is a very powerful fighter with adapt skills in hunting and mobility", "Y is a force to be reckoned with, their sturdy build lets them take less damage against any opoonent", "Z is a heavy hiter, albeit slow they can charge a heavy strike and deal a ton of damage"}
    public string fightersAbility[] = { "X has the ability to double jump", "Y has the ability to take less damage for a period of time", "Z has the ability to charge a heavy strike which deals increased damage"}
    new randomNum = new randomNum(0, 3);


}

Random rnd = new Random();
int num = rnd.Next(0, 3);
Fighters fighter01 = new Fighters(fightersName[num], fightersDescription[num], fightersAbility[num]);
Console.WriteLine("Your Fighters name is "+ fighter01.name +"/nYour Fighters Description is "+ fighter01.description+ "/nYour Fighters ability is "+ fighter01.ability);
