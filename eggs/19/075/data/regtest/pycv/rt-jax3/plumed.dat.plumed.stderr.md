**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
(download [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip))  
{% raw %}
<pre>
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
  what():  
+++ PLUMED error
+++ at PlumedMain.cpp:706, function void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
+++ message follows +++
ERROR
I cannot understand line: PYTHONCV LABEL=r ATOMS=1,2,3 IMPORT=curvature FUNCTION=r
Maybe a missing space or a typo?
[fv-az95-172:59375] *** Process received signal ***
[fv-az95-172:59375] Signal: Aborted (6)
[fv-az95-172:59375] Signal code:  (-6)
[fv-az95-172:59375] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x46210)[0x7f1c360ff210]
[fv-az95-172:59375] [ 1] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0xcb)[0x7f1c360ff18b]
[fv-az95-172:59375] [ 2] /lib/x86_64-linux-gnu/libc.so.6(abort+0x12b)[0x7f1c360de859]
[fv-az95-172:59375] [ 3] /lib/x86_64-linux-gnu/libstdc++.so.6(+0x9e911)[0x7f1c36366911]
[fv-az95-172:59375] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa38c)[0x7f1c3637238c]
[fv-az95-172:59375] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa3f7)[0x7f1c363723f7]
[fv-az95-172:59375] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xaa6a9)[0x7f1c363726a9]
[fv-az95-172:59375] [ 7] plumed(+0xf47d)[0x5649c1a3547d]
[fv-az95-172:59375] [ 8] plumed(+0x14004)[0x5649c1a3a004]
[fv-az95-172:59375] [ 9] plumed(+0xf698)[0x5649c1a35698]
[fv-az95-172:59375] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0xf3)[0x7f1c360e00b3]
[fv-az95-172:59375] [11] plumed(+0xf76e)[0x5649c1a3576e]
[fv-az95-172:59375] *** End of error message ***
</pre>
{% endraw %}
