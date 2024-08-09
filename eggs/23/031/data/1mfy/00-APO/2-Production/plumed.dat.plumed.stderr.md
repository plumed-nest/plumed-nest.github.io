**Project ID:** [plumID:23.031]({{ '/' | absolute_url }}eggs/23/031/)  
Stderr for source:  1mfy/00-APO/2-Production/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/PlumedMain.cpp:824) void PLMD::PlumedMain::readInputWords(const std::vector<std::__cxx11::basic_string<char> >&)
ERROR
I cannot understand line: SHADOW LABEL=rmsd ATOMS=rna NOPBC UPDATE=100 REFERENCE
Maybe a missing space or a typo?
[fv-az530-623:05261] *** Process received signal ***
[fv-az530-623:05261] Signal: Aborted (6)
[fv-az530-623:05261] Signal code:  (-6)
[fv-az530-623:05261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9d81042520]
[fv-az530-623:05261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9d810969fc]
[fv-az530-623:05261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9d81042476]
[fv-az530-623:05261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9d810287f3]
[fv-az530-623:05261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9d814a2b9e]
[fv-az530-623:05261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9d814ae20c]
[fv-az530-623:05261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9d814ae277]
[fv-az530-623:05261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9d814ae52b]
[fv-az530-623:05261] [ 8] plumed(+0x12f48)[0x55a81a21ef48]
[fv-az530-623:05261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9d81029d90]
[fv-az530-623:05261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9d81029e40]
[fv-az530-623:05261] [11] plumed(+0x131e5)[0x55a81a21f1e5]
[fv-az530-623:05261] *** End of error message ***
</pre>
{% endraw %}
