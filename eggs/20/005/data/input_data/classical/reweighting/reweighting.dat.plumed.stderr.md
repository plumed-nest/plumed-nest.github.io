**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s12 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:10700] *** Process received signal ***
[runnervmmklqx:10700] Signal: Aborted (6)
[runnervmmklqx:10700] Signal code:  (-6)
[runnervmmklqx:10700] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f305f845330]
[runnervmmklqx:10700] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f305f89eb2c]
[runnervmmklqx:10700] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f305f84527e]
[runnervmmklqx:10700] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f305f8288ff]
[runnervmmklqx:10700] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f305fca5ff5]
[runnervmmklqx:10700] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f305fcbb0da]
[runnervmmklqx:10700] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f305fca5a55]
[runnervmmklqx:10700] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f305fca5a6f]
[runnervmmklqx:10700] [ 8] plumed(+0x146dd)[0x55ad62f326dd]
[runnervmmklqx:10700] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f305f82a1ca]
[runnervmmklqx:10700] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f305f82a28b]
[runnervmmklqx:10700] [11] plumed(+0x15365)[0x55ad62f33365]
[runnervmmklqx:10700] *** End of error message ***
</pre>
{% endraw %}
