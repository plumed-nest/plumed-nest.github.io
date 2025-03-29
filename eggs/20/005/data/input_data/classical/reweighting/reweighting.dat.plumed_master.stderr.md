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
[fv-az1909-454:65870] *** Process received signal ***
[fv-az1909-454:65870] Signal: Aborted (6)
[fv-az1909-454:65870] Signal code:  (-6)
[fv-az1909-454:65870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faea1045330]
[fv-az1909-454:65870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faea109eb2c]
[fv-az1909-454:65870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faea104527e]
[fv-az1909-454:65870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faea10288ff]
[fv-az1909-454:65870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faea14a5ff5]
[fv-az1909-454:65870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faea14bb0da]
[fv-az1909-454:65870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faea14a5a55]
[fv-az1909-454:65870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faea14a5a6f]
[fv-az1909-454:65870] [ 8] plumed_master(+0x146dd)[0x55f068f0f6dd]
[fv-az1909-454:65870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faea102a1ca]
[fv-az1909-454:65870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faea102a28b]
[fv-az1909-454:65870] [11] plumed_master(+0x15365)[0x55f068f10365]
[fv-az1909-454:65870] *** End of error message ***
</pre>
{% endraw %}
