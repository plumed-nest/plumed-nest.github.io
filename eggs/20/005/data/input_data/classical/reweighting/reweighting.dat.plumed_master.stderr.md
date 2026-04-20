**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @19 : keyword ARG is compulsory for this action
[runnervmeorf1:09481] *** Process received signal ***
[runnervmeorf1:09481] Signal: Aborted (6)
[runnervmeorf1:09481] Signal code:  (-6)
[runnervmeorf1:09481] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe2a3845330]
[runnervmeorf1:09481] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe2a389eb2c]
[runnervmeorf1:09481] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe2a384527e]
[runnervmeorf1:09481] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2a38288ff]
[runnervmeorf1:09481] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2a3ca5ff5]
[runnervmeorf1:09481] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2a3cbb0da]
[runnervmeorf1:09481] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2a3ca5a55]
[runnervmeorf1:09481] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2a3ca5a6f]
[runnervmeorf1:09481] [ 8] plumed_master(+0x146dd)[0x5650e9fd26dd]
[runnervmeorf1:09481] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe2a382a1ca]
[runnervmeorf1:09481] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe2a382a28b]
[runnervmeorf1:09481] [11] plumed_master(+0x15365)[0x5650e9fd3365]
[runnervmeorf1:09481] *** End of error message ***
</pre>
{% endraw %}
