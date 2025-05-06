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
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[fv-az1050-229:67335] *** Process received signal ***
[fv-az1050-229:67335] Signal: Aborted (6)
[fv-az1050-229:67335] Signal code:  (-6)
[fv-az1050-229:67335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc20d645330]
[fv-az1050-229:67335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc20d69eb2c]
[fv-az1050-229:67335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc20d64527e]
[fv-az1050-229:67335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc20d6288ff]
[fv-az1050-229:67335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc20daa5ff5]
[fv-az1050-229:67335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc20dabb0da]
[fv-az1050-229:67335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc20daa5a55]
[fv-az1050-229:67335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc20daa5a6f]
[fv-az1050-229:67335] [ 8] plumed_master(+0x146dd)[0x55e7e2ad26dd]
[fv-az1050-229:67335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc20d62a1ca]
[fv-az1050-229:67335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc20d62a28b]
[fv-az1050-229:67335] [11] plumed_master(+0x15365)[0x55e7e2ad3365]
[fv-az1050-229:67335] *** End of error message ***
</pre>
{% endraw %}
