**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az1720-841:09874] *** Process received signal ***
[fv-az1720-841:09874] Signal: Aborted (6)
[fv-az1720-841:09874] Signal code:  (-6)
[fv-az1720-841:09874] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb1d4845330]
[fv-az1720-841:09874] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb1d489eb2c]
[fv-az1720-841:09874] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb1d484527e]
[fv-az1720-841:09874] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb1d48288ff]
[fv-az1720-841:09874] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb1d4ca5ff5]
[fv-az1720-841:09874] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb1d4cbb0da]
[fv-az1720-841:09874] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb1d4ca5a55]
[fv-az1720-841:09874] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb1d4ca5a6f]
[fv-az1720-841:09874] [ 8] plumed_master(+0x146dd)[0x55c417f736dd]
[fv-az1720-841:09874] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb1d482a1ca]
[fv-az1720-841:09874] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb1d482a28b]
[fv-az1720-841:09874] [11] plumed_master(+0x15365)[0x55c417f74365]
[fv-az1720-841:09874] *** End of error message ***
</pre>
{% endraw %}
