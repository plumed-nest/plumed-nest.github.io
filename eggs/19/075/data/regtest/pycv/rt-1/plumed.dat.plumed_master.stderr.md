**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:986) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&, const bool&)
ERROR
I cannot understand line: PYTHONCV LABEL=cv1 ATOMS=1,4 IMPORT=pycv FUNCTION=cv1
Maybe a missing space or a typo?
[fv-az985-228:69824] *** Process received signal ***
[fv-az985-228:69824] Signal: Aborted (6)
[fv-az985-228:69824] Signal code:  (-6)
[fv-az985-228:69824] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f38ce642520]
[fv-az985-228:69824] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f38ce6969fc]
[fv-az985-228:69824] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f38ce642476]
[fv-az985-228:69824] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f38ce6287f3]
[fv-az985-228:69824] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7f38ceaa4f26]
[fv-az985-228:69824] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7f38ceab6d9c]
[fv-az985-228:69824] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7f38ceab6e07]
[fv-az985-228:69824] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f38ceab70bb]
[fv-az985-228:69824] [ 8] plumed_master(+0x12e7f)[0x55d9affbee7f]
[fv-az985-228:69824] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f38ce629d90]
[fv-az985-228:69824] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f38ce629e40]
[fv-az985-228:69824] [11] plumed_master(+0x13115)[0x55d9affbf115]
[fv-az985-228:69824] *** End of error message ***
</pre>
{% endraw %}
