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
[fv-az790-36:67980] *** Process received signal ***
[fv-az790-36:67980] Signal: Aborted (6)
[fv-az790-36:67980] Signal code:  (-6)
[fv-az790-36:67980] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81b1645330]
[fv-az790-36:67980] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81b169eb2c]
[fv-az790-36:67980] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81b164527e]
[fv-az790-36:67980] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81b16288ff]
[fv-az790-36:67980] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81b1aa5ff5]
[fv-az790-36:67980] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81b1abb0da]
[fv-az790-36:67980] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81b1aa5a55]
[fv-az790-36:67980] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81b1aa5a6f]
[fv-az790-36:67980] [ 8] plumed_master(+0x146dd)[0x55d4186da6dd]
[fv-az790-36:67980] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81b162a1ca]
[fv-az790-36:67980] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81b162a28b]
[fv-az790-36:67980] [11] plumed_master(+0x15365)[0x55d4186db365]
[fv-az790-36:67980] *** End of error message ***
</pre>
{% endraw %}
