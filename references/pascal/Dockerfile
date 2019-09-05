FROM nacyot/pascal-fp_compiler:apt
COPY example.pas /tmp/
COPY intro /tmp/
CMD /tmp/intro && fpc /tmp/example.pas && /tmp/example
