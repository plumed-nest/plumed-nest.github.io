**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az985-228:69391] *** Process received signal ***
[fv-az985-228:69391] Signal: Aborted (6)
[fv-az985-228:69391] Signal code:  (-6)
[fv-az985-228:69391] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f07c4642520]
[fv-az985-228:69391] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f07c46969fc]
[fv-az985-228:69391] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f07c4642476]
[fv-az985-228:69391] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f07c46287f3]
[fv-az985-228:69391] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f07c4aa4f26]
[fv-az985-228:69391] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f07c4ab6d9c]
[fv-az985-228:69391] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f07c4ab6e07]
[fv-az985-228:69391] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f07c4ab70bb]
[fv-az985-228:69391] [ 8] plumed(+0x12f48)[0x565417428f48]
[fv-az985-228:69391] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f07c4629d90]
[fv-az985-228:69391] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f07c4629e40]
[fv-az985-228:69391] [11] plumed(+0x131e5)[0x5654174291e5]
[fv-az985-228:69391] *** End of error message ***
</pre>
{% endraw %}
