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
[pkrvmf6wy0o8zjz:67019] *** Process received signal ***
[pkrvmf6wy0o8zjz:67019] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:67019] Signal code:  (-6)
[pkrvmf6wy0o8zjz:67019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa98ec45330]
[pkrvmf6wy0o8zjz:67019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa98ec9eb2c]
[pkrvmf6wy0o8zjz:67019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa98ec4527e]
[pkrvmf6wy0o8zjz:67019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa98ec288ff]
[pkrvmf6wy0o8zjz:67019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa98f0a5ff5]
[pkrvmf6wy0o8zjz:67019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa98f0bb0da]
[pkrvmf6wy0o8zjz:67019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa98f0a5a55]
[pkrvmf6wy0o8zjz:67019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa98f0a5a6f]
[pkrvmf6wy0o8zjz:67019] [ 8] plumed(+0x146dd)[0x55eb50e396dd]
[pkrvmf6wy0o8zjz:67019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa98ec2a1ca]
[pkrvmf6wy0o8zjz:67019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa98ec2a28b]
[pkrvmf6wy0o8zjz:67019] [11] plumed(+0x15365)[0x55eb50e3a365]
[pkrvmf6wy0o8zjz:67019] *** End of error message ***
</pre>
{% endraw %}
