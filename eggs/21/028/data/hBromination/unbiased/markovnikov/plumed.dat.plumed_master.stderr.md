**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmvrwv9:10536] *** Process received signal ***
[runnervmvrwv9:10536] Signal: Aborted (6)
[runnervmvrwv9:10536] Signal code:  (-6)
[runnervmvrwv9:10536] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3490645330]
[runnervmvrwv9:10536] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f349069eb2c]
[runnervmvrwv9:10536] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f349064527e]
[runnervmvrwv9:10536] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34906288ff]
[runnervmvrwv9:10536] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3490aa5ff5]
[runnervmvrwv9:10536] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3490abb0da]
[runnervmvrwv9:10536] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3490aa5a55]
[runnervmvrwv9:10536] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3490aa5a6f]
[runnervmvrwv9:10536] [ 8] plumed_master(+0x146dd)[0x55fc5b47d6dd]
[runnervmvrwv9:10536] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f349062a1ca]
[runnervmvrwv9:10536] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f349062a28b]
[runnervmvrwv9:10536] [11] plumed_master(+0x15365)[0x55fc5b47e365]
[runnervmvrwv9:10536] *** End of error message ***
</pre>
{% endraw %}
