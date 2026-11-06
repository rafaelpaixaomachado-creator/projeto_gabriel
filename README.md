## 📄 Estrutura do projeto

### index.php

```php
<?php

$page_title = 'Hotel Millane';

require_once 'pages/partials/head.php';
require_once 'pages/partials/nav.php';

require_once 'pages/home.php';

require_once 'pages/partials/footer.php';

?>
```

### nav.php

```php
<header>
    <nav>
        <a href="index.php">Início</a>
        <a href="pages/cadastro-quarto.php">Cadastrar quarto</a>
        <a href="pages/listagem-quarto.php">Acomodações</a>
    </nav>
</header>
```
