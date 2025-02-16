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
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[fv-az1112-175:67645] *** Process received signal ***
[fv-az1112-175:67645] Signal: Aborted (6)
[fv-az1112-175:67645] Signal code:  (-6)
[fv-az1112-175:67645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe45e645330]
[fv-az1112-175:67645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe45e69eb2c]
[fv-az1112-175:67645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe45e64527e]
[fv-az1112-175:67645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe45e6288ff]
[fv-az1112-175:67645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe45eaa5ff5]
[fv-az1112-175:67645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe45eabb0da]
[fv-az1112-175:67645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe45eaa5a55]
[fv-az1112-175:67645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe45eaa5a6f]
[fv-az1112-175:67645] [ 8] plumed_master(+0x146dd)[0x565362a436dd]
[fv-az1112-175:67645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe45e62a1ca]
[fv-az1112-175:67645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe45e62a28b]
[fv-az1112-175:67645] [11] plumed_master(+0x15365)[0x565362a44365]
[fv-az1112-175:67645] *** End of error message ***
</pre>
{% endraw %}
