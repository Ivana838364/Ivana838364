use Tesla\JMBG\Generator;

$gen = new Generator;

// Returns valid random JMBG
$gen->fake();

// Override params [day, month, year, region, gender]
$gen->fake
