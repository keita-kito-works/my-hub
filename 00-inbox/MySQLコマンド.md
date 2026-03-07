### MySQLコマンド集

**起動**

管理者でコマンドプロンプトを実行して以下コマンドを入力。
```
net start MySQL57
```

**ログイン**

```
mysql --user=root --password
```

**ログアウト**

```
exit;
```

**データベース操作**

```
show databases;
CREATE DATABASE DB_NAME CHARACTER SET utf8mb4;
use DB_NAME
```

**テーブル操作**

```
desc TABLE_NAME;
```

