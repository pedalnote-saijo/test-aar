# test-aar

test-aar パブリックリポジトリ

hogeaar lib

参考: qiita.com/WorldDownTown/items/0cf2efeddd58b0b2483d

使い方
1 プロジェクトレベルのbuild.gradle: allprojects > repogitory > maven { url 'https://raw.github.com/pedalnote-saijo/test-aar/master/repository' } 追加
2 アプリレベルのbuild.gradle: dependencies > implementation 'jp.forista.hogeaar:hogeaar-saijo:1.0.0' 追加 (${groupId}:${artifactId}:${version}

