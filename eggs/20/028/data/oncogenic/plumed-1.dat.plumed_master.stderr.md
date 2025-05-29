**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:152) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[pkrvmf6wy0o8zjz:67086] *** Process received signal ***
[pkrvmf6wy0o8zjz:67086] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:67086] Signal code:  (-6)
[pkrvmf6wy0o8zjz:67086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7558645330]
[pkrvmf6wy0o8zjz:67086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f755869eb2c]
[pkrvmf6wy0o8zjz:67086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f755864527e]
[pkrvmf6wy0o8zjz:67086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f75586288ff]
[pkrvmf6wy0o8zjz:67086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7558aa5ff5]
[pkrvmf6wy0o8zjz:67086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7558abb0da]
[pkrvmf6wy0o8zjz:67086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7558aa5a55]
[pkrvmf6wy0o8zjz:67086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7558aa5a6f]
[pkrvmf6wy0o8zjz:67086] [ 8] plumed_master(+0x146dd)[0x560cf1b766dd]
[pkrvmf6wy0o8zjz:67086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f755862a1ca]
[pkrvmf6wy0o8zjz:67086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f755862a28b]
[pkrvmf6wy0o8zjz:67086] [11] plumed_master(+0x15365)[0x560cf1b77365]
[pkrvmf6wy0o8zjz:67086] *** End of error message ***
</pre>
{% endraw %}
