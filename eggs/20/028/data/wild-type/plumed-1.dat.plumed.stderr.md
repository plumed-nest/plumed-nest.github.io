**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[fv-az1278-681:67067] *** Process received signal ***
[fv-az1278-681:67067] Signal: Aborted (6)
[fv-az1278-681:67067] Signal code:  (-6)
[fv-az1278-681:67067] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64ada45330]
[fv-az1278-681:67067] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64ada9eb2c]
[fv-az1278-681:67067] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64ada4527e]
[fv-az1278-681:67067] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64ada288ff]
[fv-az1278-681:67067] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64adea5ff5]
[fv-az1278-681:67067] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64adebb0da]
[fv-az1278-681:67067] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64adea5a55]
[fv-az1278-681:67067] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64adea5a6f]
[fv-az1278-681:67067] [ 8] plumed(+0x146dd)[0x5605425c36dd]
[fv-az1278-681:67067] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64ada2a1ca]
[fv-az1278-681:67067] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64ada2a28b]
[fv-az1278-681:67067] [11] plumed(+0x15365)[0x5605425c4365]
[fv-az1278-681:67067] *** End of error message ***
</pre>
{% endraw %}
