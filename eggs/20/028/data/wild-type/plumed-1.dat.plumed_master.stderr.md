**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:158) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[pkrvm7jw40e0xgp:11657] *** Process received signal ***
[pkrvm7jw40e0xgp:11657] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11657] Signal code:  (-6)
[pkrvm7jw40e0xgp:11657] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f35de845330]
[pkrvm7jw40e0xgp:11657] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f35de89eb2c]
[pkrvm7jw40e0xgp:11657] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f35de84527e]
[pkrvm7jw40e0xgp:11657] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35de8288ff]
[pkrvm7jw40e0xgp:11657] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35deca5ff5]
[pkrvm7jw40e0xgp:11657] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35decbb0da]
[pkrvm7jw40e0xgp:11657] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35deca5a55]
[pkrvm7jw40e0xgp:11657] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35deca5a6f]
[pkrvm7jw40e0xgp:11657] [ 8] plumed_master(+0x146dd)[0x5594bf4ac6dd]
[pkrvm7jw40e0xgp:11657] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f35de82a1ca]
[pkrvm7jw40e0xgp:11657] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f35de82a28b]
[pkrvm7jw40e0xgp:11657] [11] plumed_master(+0x15365)[0x5594bf4ad365]
[pkrvm7jw40e0xgp:11657] *** End of error message ***
</pre>
{% endraw %}
