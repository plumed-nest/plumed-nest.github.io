**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[runnervmvrwv9:04740] *** Process received signal ***
[runnervmvrwv9:04740] Signal: Aborted (6)
[runnervmvrwv9:04740] Signal code:  (-6)
[runnervmvrwv9:04740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41ecc45330]
[runnervmvrwv9:04740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41ecc9eb2c]
[runnervmvrwv9:04740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41ecc4527e]
[runnervmvrwv9:04740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41ecc288ff]
[runnervmvrwv9:04740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41ed0a5ff5]
[runnervmvrwv9:04740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41ed0bb0da]
[runnervmvrwv9:04740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41ed0a5a55]
[runnervmvrwv9:04740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41ed0a5a6f]
[runnervmvrwv9:04740] [ 8] plumed_master(+0x146dd)[0x55693a19a6dd]
[runnervmvrwv9:04740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41ecc2a1ca]
[runnervmvrwv9:04740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41ecc2a28b]
[runnervmvrwv9:04740] [11] plumed_master(+0x15365)[0x55693a19b365]
[runnervmvrwv9:04740] *** End of error message ***
</pre>
{% endraw %}
