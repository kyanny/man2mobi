NAME
    man2mobi - マニュアルページを .mobi 形式に変換する

SYNOPSIS
    $ man2mobi name

      または

      man2kindle -f foo@example.com -t bar@example.com name

DESCRIPTION
    man2mobi は name として指定されたマニュアルページを
    .mobi 形式に変換する。変換には man2html(1) と Amazon
    Kindle's Publishing Program で配布されている KindleGen
    が必要である。 KindleGen のアーカイブに含まれている
    kindlegen
    をパスの通ったところへ配置しておくこと。なお、
    KindleGen の利用には別途 KINDLEGEN SOFTWARE END USER LICENSE
    AGREEMENT への同意が必要である。

    man2kindle は man2mobi へのシンボリックリンクである。
    man2kindle は name として指定されたマニュアルページを
    .mobi
    形式に変換し、そのファイルをメッセージに添付して
    コマンドラインオプションで指定されたメールアドレ
    スに送信する。メールの送信には mutt(1)
    が必要である。

    Kindle に直接メールで .mobi
    形式のファイルを送信する場合、 @kindle.com または
    @free.kindle.com
    というドメインのメールアドレスが利用できる。これ
    らのアドレスにメールを送信するには、Manage Your Kindle
    ページで送信元メールアドレスを許可する必要がある
    。詳細は Sending Personal Documents to Kindle
    ページを参照のこと。

AUTHOR
    Kensuke Kaneko <kyanny at gmail.com>

SEE ALSO
    *   man2html(1)

    *   mutt(1)

    *   Amazon Kindle's Publishing Program
        http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000234621

    *   Sending Personal Documents to Kindle
        http://www.amazon.com/gp/help/customer/display.html?nodeId=200505520
        &#email

    *   Manage Your Kindle http://www.amazon.com/manageyourkindle

LICENSE
    This library is free software; you can redistribute it and/or modify it
    under the same terms as Perl itself.

