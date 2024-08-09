**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: PYTHONCV LABEL=r ATOMS=1,2,3 IMPORT=curvature FUNCTION=r
Maybe a missing space or a typo?
[fv-az1269-668:06464] *** Process received signal ***
[fv-az1269-668:06464] Signal: Aborted (6)
[fv-az1269-668:06464] Signal code:  (-6)
[fv-az1269-668:06464] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fc873842520]
[fv-az1269-668:06464] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fc8738969fc]
[fv-az1269-668:06464] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fc873842476]
[fv-az1269-668:06464] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fc8738287f3]
[fv-az1269-668:06464] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fc873ca2b9e]
[fv-az1269-668:06464] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fc873cae20c]
[fv-az1269-668:06464] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fc873cae277]
[fv-az1269-668:06464] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fc873cae52b]
[fv-az1269-668:06464] [ 8] plumed(+0x12f48)[0x5647ae3a3f48]
[fv-az1269-668:06464] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fc873829d90]
[fv-az1269-668:06464] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fc873829e40]
[fv-az1269-668:06464] [11] plumed(+0x131e5)[0x5647ae3a41e5]
[fv-az1269-668:06464] *** End of error message ***
</pre>
{% endraw %}
