**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmvrwv9:11307] *** Process received signal ***
[runnervmvrwv9:11307] Signal: Aborted (6)
[runnervmvrwv9:11307] Signal code:  (-6)
[runnervmvrwv9:11307] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2b42845330]
[runnervmvrwv9:11307] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2b4289eb2c]
[runnervmvrwv9:11307] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2b4284527e]
[runnervmvrwv9:11307] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2b428288ff]
[runnervmvrwv9:11307] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2b42ca5ff5]
[runnervmvrwv9:11307] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2b42cbb0da]
[runnervmvrwv9:11307] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2b42ca5a55]
[runnervmvrwv9:11307] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2b42ca5a6f]
[runnervmvrwv9:11307] [ 8] plumed(+0x146dd)[0x55ab4715d6dd]
[runnervmvrwv9:11307] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2b4282a1ca]
[runnervmvrwv9:11307] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2b4282a28b]
[runnervmvrwv9:11307] [11] plumed(+0x15365)[0x55ab4715e365]
[runnervmvrwv9:11307] *** End of error message ***
</pre>
{% endraw %}
