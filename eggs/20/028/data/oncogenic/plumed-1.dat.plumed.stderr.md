**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvm7jw40e0xgp:11692] *** Process received signal ***
[pkrvm7jw40e0xgp:11692] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11692] Signal code:  (-6)
[pkrvm7jw40e0xgp:11692] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa8dc645330]
[pkrvm7jw40e0xgp:11692] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa8dc69eb2c]
[pkrvm7jw40e0xgp:11692] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa8dc64527e]
[pkrvm7jw40e0xgp:11692] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8dc6288ff]
[pkrvm7jw40e0xgp:11692] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8dcaa5ff5]
[pkrvm7jw40e0xgp:11692] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8dcabb0da]
[pkrvm7jw40e0xgp:11692] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8dcaa5a55]
[pkrvm7jw40e0xgp:11692] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8dcaa5a6f]
[pkrvm7jw40e0xgp:11692] [ 8] plumed(+0x146dd)[0x55a174f596dd]
[pkrvm7jw40e0xgp:11692] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa8dc62a1ca]
[pkrvm7jw40e0xgp:11692] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa8dc62a28b]
[pkrvm7jw40e0xgp:11692] [11] plumed(+0x15365)[0x55a174f5a365]
[pkrvm7jw40e0xgp:11692] *** End of error message ***
</pre>
{% endraw %}
