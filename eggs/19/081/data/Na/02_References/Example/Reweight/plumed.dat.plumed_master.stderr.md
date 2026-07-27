**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/02_References/Example/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:10709] *** Process received signal ***
[runnervmvrwv9:10709] Signal: Aborted (6)
[runnervmvrwv9:10709] Signal code:  (-6)
[runnervmvrwv9:10709] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4bbe445330]
[runnervmvrwv9:10709] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4bbe49eb2c]
[runnervmvrwv9:10709] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4bbe44527e]
[runnervmvrwv9:10709] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4bbe4288ff]
[runnervmvrwv9:10709] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4bbe8a5ff5]
[runnervmvrwv9:10709] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4bbe8bb0da]
[runnervmvrwv9:10709] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4bbe8a5a55]
[runnervmvrwv9:10709] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4bbe8a5a6f]
[runnervmvrwv9:10709] [ 8] plumed_master(+0x146dd)[0x557b9d4826dd]
[runnervmvrwv9:10709] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4bbe42a1ca]
[runnervmvrwv9:10709] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4bbe42a28b]
[runnervmvrwv9:10709] [11] plumed_master(+0x15365)[0x557b9d483365]
[runnervmvrwv9:10709] *** End of error message ***
</pre>
{% endraw %}
