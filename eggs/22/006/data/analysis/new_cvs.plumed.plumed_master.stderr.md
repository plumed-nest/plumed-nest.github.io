**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/new_cvs.plumed   
Download: [zipped raw stdout](new_cvs.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](new_cvs.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s43 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmvrwv9:08446] *** Process received signal ***
[runnervmvrwv9:08446] Signal: Aborted (6)
[runnervmvrwv9:08446] Signal code:  (-6)
[runnervmvrwv9:08446] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f64c45330]
[runnervmvrwv9:08446] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f64c9eb2c]
[runnervmvrwv9:08446] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f64c4527e]
[runnervmvrwv9:08446] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f64c288ff]
[runnervmvrwv9:08446] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f650a5ff5]
[runnervmvrwv9:08446] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f650bb0da]
[runnervmvrwv9:08446] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f650a5a55]
[runnervmvrwv9:08446] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f650a5a6f]
[runnervmvrwv9:08446] [ 8] plumed_master(+0x146dd)[0x5622c00036dd]
[runnervmvrwv9:08446] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f64c2a1ca]
[runnervmvrwv9:08446] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f64c2a28b]
[runnervmvrwv9:08446] [11] plumed_master(+0x15365)[0x5622c0004365]
[runnervmvrwv9:08446] *** End of error message ***
</pre>
{% endraw %}
