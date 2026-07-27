**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:10693] *** Process received signal ***
[runnervmvrwv9:10693] Signal: Aborted (6)
[runnervmvrwv9:10693] Signal code:  (-6)
[runnervmvrwv9:10693] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f92bb245330]
[runnervmvrwv9:10693] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f92bb29eb2c]
[runnervmvrwv9:10693] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f92bb24527e]
[runnervmvrwv9:10693] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f92bb2288ff]
[runnervmvrwv9:10693] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f92bb6a5ff5]
[runnervmvrwv9:10693] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f92bb6bb0da]
[runnervmvrwv9:10693] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f92bb6a5a55]
[runnervmvrwv9:10693] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f92bb6a5a6f]
[runnervmvrwv9:10693] [ 8] plumed(+0x146dd)[0x5635b1c276dd]
[runnervmvrwv9:10693] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f92bb22a1ca]
[runnervmvrwv9:10693] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f92bb22a28b]
[runnervmvrwv9:10693] [11] plumed(+0x15365)[0x5635b1c28365]
[runnervmvrwv9:10693] *** End of error message ***
</pre>
{% endraw %}
