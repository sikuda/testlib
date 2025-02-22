Test empty library for composer v2<br>
<br>
1. Add library into project<br>
   composer require sikuda\testlib<br>
<br>
2. Make php file in project<br>
<-?-php<br>
declare(strict_types = 1);<br>
<br>
namespace Sikuda\TestlibProject;<br>
require __DIR__ . '/../vendor/autoload.php';<br>
<br>
use Sikuda\Testlib\TestLib;<br>
<br>
$test = new TestLib();<br>
$test->hello();<br>
   




