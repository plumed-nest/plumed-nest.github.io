**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:04320] *** Process received signal ***
[runnervmvrwv9:04320] Signal: Aborted (6)
[runnervmvrwv9:04320] Signal code:  (-6)
[runnervmvrwv9:04320] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a17c45330]
[runnervmvrwv9:04320] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a17c9eb2c]
[runnervmvrwv9:04320] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a17c4527e]
[runnervmvrwv9:04320] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a17c288ff]
[runnervmvrwv9:04320] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a180a5ff5]
[runnervmvrwv9:04320] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a180bb0da]
[runnervmvrwv9:04320] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a180a5a55]
[runnervmvrwv9:04320] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a180a5a6f]
[runnervmvrwv9:04320] [ 8] plumed(+0x146dd)[0x555ab21546dd]
[runnervmvrwv9:04320] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a17c2a1ca]
[runnervmvrwv9:04320] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a17c2a28b]
[runnervmvrwv9:04320] [11] plumed(+0x15365)[0x555ab2155365]
[runnervmvrwv9:04320] *** End of error message ***
</pre>
{% endraw %}
