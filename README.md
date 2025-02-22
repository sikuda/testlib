Test empty library for composer v2

1. Add library into project
   composer require sikuda\testlib

2. Make php file in project
<-?-php
declare(strict_types = 1);

namespace Sikuda\TestlibProject;
require __DIR__ . '/../vendor/autoload.php';

use Sikuda\Testlib\TestLib;

$test = new TestLib();
$test->hello();
   




