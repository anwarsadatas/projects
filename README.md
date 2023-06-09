# projects
########################################################################
Team Manager Project
################################################################
This is a team manager project where by team manager register and create only one team can authenticated. Inside the team the team manager can add players who come from different countries.The team manager can buy players from other teams if they have sufficient if not they will not be allowed to buy player if the money balance of the team is less than the price of the player then operation will not be allowed.
If team sells a player the money balance of the team will be incremented.

The players and team can be edited.Country is under database/seeders directory which contains some of the countries.

You can the program by -php artisan migrate 
                        -php artisan make:seeder CountrySeeder
                        -php artisan serve
                        -npm run dev

########################################################################################## 
