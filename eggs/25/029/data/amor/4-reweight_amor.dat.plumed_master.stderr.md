**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s33 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:04336] *** Process received signal ***
[runnervmvrwv9:04336] Signal: Aborted (6)
[runnervmvrwv9:04336] Signal code:  (-6)
[runnervmvrwv9:04336] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77c9045330]
[runnervmvrwv9:04336] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77c909eb2c]
[runnervmvrwv9:04336] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77c904527e]
[runnervmvrwv9:04336] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77c90288ff]
[runnervmvrwv9:04336] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77c94a5ff5]
[runnervmvrwv9:04336] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77c94bb0da]
[runnervmvrwv9:04336] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77c94a5a55]
[runnervmvrwv9:04336] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77c94a5a6f]
[runnervmvrwv9:04336] [ 8] plumed_master(+0x146dd)[0x562d72d606dd]
[runnervmvrwv9:04336] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77c902a1ca]
[runnervmvrwv9:04336] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77c902a28b]
[runnervmvrwv9:04336] [11] plumed_master(+0x15365)[0x562d72d61365]
[runnervmvrwv9:04336] *** End of error message ***
</pre>
{% endraw %}
