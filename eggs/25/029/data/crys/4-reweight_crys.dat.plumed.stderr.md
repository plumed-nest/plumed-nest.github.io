**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./crys/4-reweight_crys.dat   
Download: [zipped raw stdout](4-reweight_crys.dat.plumed.stdout.txt.zip) - [zipped raw stderr](4-reweight_crys.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:04752] *** Process received signal ***
[runnervmmklqx:04752] Signal: Aborted (6)
[runnervmmklqx:04752] Signal code:  (-6)
[runnervmmklqx:04752] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc823e45330]
[runnervmmklqx:04752] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc823e9eb2c]
[runnervmmklqx:04752] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc823e4527e]
[runnervmmklqx:04752] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc823e288ff]
[runnervmmklqx:04752] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8242a5ff5]
[runnervmmklqx:04752] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8242bb0da]
[runnervmmklqx:04752] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8242a5a55]
[runnervmmklqx:04752] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8242a5a6f]
[runnervmmklqx:04752] [ 8] plumed(+0x146dd)[0x561fd53796dd]
[runnervmmklqx:04752] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc823e2a1ca]
[runnervmmklqx:04752] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc823e2a28b]
[runnervmmklqx:04752] [11] plumed(+0x15365)[0x561fd537a365]
[runnervmmklqx:04752] *** End of error message ***
</pre>
{% endraw %}
