**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:10575] *** Process received signal ***
[runnervmvrwv9:10575] Signal: Aborted (6)
[runnervmvrwv9:10575] Signal code:  (-6)
[runnervmvrwv9:10575] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f355f645330]
[runnervmvrwv9:10575] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f355f69eb2c]
[runnervmvrwv9:10575] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f355f64527e]
[runnervmvrwv9:10575] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f355f6288ff]
[runnervmvrwv9:10575] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f355faa5ff5]
[runnervmvrwv9:10575] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f355fabb0da]
[runnervmvrwv9:10575] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f355faa5a55]
[runnervmvrwv9:10575] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f355faa5a6f]
[runnervmvrwv9:10575] [ 8] plumed(+0x146dd)[0x55d6693106dd]
[runnervmvrwv9:10575] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f355f62a1ca]
[runnervmvrwv9:10575] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f355f62a28b]
[runnervmvrwv9:10575] [11] plumed(+0x15365)[0x55d669311365]
[runnervmvrwv9:10575] *** End of error message ***
</pre>
{% endraw %}
