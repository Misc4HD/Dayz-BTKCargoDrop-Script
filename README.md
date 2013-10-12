Dayz-BTKCargoDrop-Script
========================

In progress i try to add 1 script a day.


1.Download BTKCargoDrop <a href="http://d.pr/hBcz">HERE</a>

2.Copy and paste the BTK folder to your mission folder (just BTK nothing else)

3.Add this line to your init.sqf

    execVM "BTK\Cargo Drop\Start.sqf";
    
4.To disable the feature at all, do the comment thing

    // execVM "BTK\Cargo Drop\Start.sqf";
    
5.Eddit your BattleEye Filters in the setpos.txt set the numbers in front to 1 in the createvehicle.txt set the number infront Parachute to 1 (if you don't find it i have the BattleEye filters uploaded look in to them)

6.You can change the loadable objects by editing the "BTK\Cargo Drop\Settings_Objects.sqf" and "BTK\Cargo Drop\Settings_Transporter.sqf" files.
