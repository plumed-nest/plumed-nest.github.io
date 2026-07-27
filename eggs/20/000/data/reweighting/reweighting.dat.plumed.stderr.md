**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:09619] *** Process received signal ***
[runnervmvrwv9:09619] Signal: Aborted (6)
[runnervmvrwv9:09619] Signal code:  (-6)
[runnervmvrwv9:09619] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02f1a45330]
[runnervmvrwv9:09619] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02f1a9eb2c]
[runnervmvrwv9:09619] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02f1a4527e]
[runnervmvrwv9:09619] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02f1a288ff]
[runnervmvrwv9:09619] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02f1ea5ff5]
[runnervmvrwv9:09619] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02f1ebb0da]
[runnervmvrwv9:09619] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02f1ea5a55]
[runnervmvrwv9:09619] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02f1ea5a6f]
[runnervmvrwv9:09619] [ 8] plumed(+0x146dd)[0x5570d40a76dd]
[runnervmvrwv9:09619] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02f1a2a1ca]
[runnervmvrwv9:09619] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02f1a2a28b]
[runnervmvrwv9:09619] [11] plumed(+0x15365)[0x5570d40a8365]
[runnervmvrwv9:09619] *** End of error message ***
</pre>
{% endraw %}
