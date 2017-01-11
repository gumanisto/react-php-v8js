# Example / Пример испльзования

Относительно оригинала, пример был переработан. Исходный пример вываливался с ошибкой и содержал не верные даже ссылки

## 

include './ReactJS.php';

$rjs = new ReactJS(
  // location of React's code
  file_get_contents('build/react-bundle.js'),
  // app code
  file_get_contents('build/table.js')
);

// data to be passed to the component
$data =
  array('data' => array(
    array(1, 2, 3),
    array(4, 1, 6),
    array(7, 8, 1)
  ));

  