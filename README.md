Arabic RTLize
==========

Arabic RTLize is a python library written by HasenJ and repackaged by James Dennis

HasenJ's code is available here :: http://github.com/hasenj/arabic-writer

Usage
-----

    from arabic_rtlize.process import rtlize
    ltr_word = '\xda\xa9\xd9\x85\xdb\x8c\xd9\xb9\xdb\x8c'
    rtl_word = rtlize(unicode(lrt_word, 'UTF-8'))

Install
-------

python ./setup.py install

Hasan        <<hasan.aljudy@gmail.com>>
James Dennis <<jd@j2labs.net>>
