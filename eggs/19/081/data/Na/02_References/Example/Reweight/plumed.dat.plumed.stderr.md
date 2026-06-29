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
[runnervmmklqx:11662] *** Process received signal ***
[runnervmmklqx:11662] Signal: Aborted (6)
[runnervmmklqx:11662] Signal code:  (-6)
[runnervmmklqx:11662] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a41045330]
[runnervmmklqx:11662] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a4109eb2c]
[runnervmmklqx:11662] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a4104527e]
[runnervmmklqx:11662] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a410288ff]
[runnervmmklqx:11662] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a414a5ff5]
[runnervmmklqx:11662] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a414bb0da]
[runnervmmklqx:11662] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a414a5a55]
[runnervmmklqx:11662] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a414a5a6f]
[runnervmmklqx:11662] [ 8] plumed(+0x146dd)[0x5599795a46dd]
[runnervmmklqx:11662] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a4102a1ca]
[runnervmmklqx:11662] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a4102a28b]
[runnervmmklqx:11662] [11] plumed(+0x15365)[0x5599795a5365]
[runnervmmklqx:11662] *** End of error message ***
</pre>
{% endraw %}
