**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s23 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09636] *** Process received signal ***
[runnervmvrwv9:09636] Signal: Aborted (6)
[runnervmvrwv9:09636] Signal code:  (-6)
[runnervmvrwv9:09636] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf8dc45330]
[runnervmvrwv9:09636] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf8dc9eb2c]
[runnervmvrwv9:09636] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf8dc4527e]
[runnervmvrwv9:09636] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf8dc288ff]
[runnervmvrwv9:09636] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf8e0a5ff5]
[runnervmvrwv9:09636] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf8e0bb0da]
[runnervmvrwv9:09636] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf8e0a5a55]
[runnervmvrwv9:09636] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf8e0a5a6f]
[runnervmvrwv9:09636] [ 8] plumed(+0x146dd)[0x559ecae0a6dd]
[runnervmvrwv9:09636] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf8dc2a1ca]
[runnervmvrwv9:09636] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf8dc2a28b]
[runnervmvrwv9:09636] [11] plumed(+0x15365)[0x559ecae0b365]
[runnervmvrwv9:09636] *** End of error message ***
</pre>
{% endraw %}
