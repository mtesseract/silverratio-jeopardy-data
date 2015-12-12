objects = advanced_1.jdc beginner_1.jdc intermediate_1.jdc intermediate_2.jdc 

all: $(objects)

compiler = ../../dist/build/jeopardy-compiler/jeopardy-compiler

$(objects): %.jdc: %.jd
	$(compiler) $< $@
