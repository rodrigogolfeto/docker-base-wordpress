// Define o método de acesso ao sistema de arquivos do WordPress como "direct".
// Isso permite que o WordPress faça alterações diretamente no sistema de arquivos sem solicitar credenciais FTP/SSH.
// NOTA: Use com cuidado, pois pode representar um risco de segurança se usado em ambientes sem as permissões adequadas.
define('FS_METHOD', 'direct');