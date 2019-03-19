bin_PROGRAMS = strom
strom_SOURCES = main.cpp \
				node.hpp \
				tree.hpp \
				tree_manip.hpp \
				xstrom.hpp \
				data.hpp \
				split.hpp \
				tree_summary.hpp \
				likelihood.hpp \
				strom.hpp \
				model.hpp \
				lot.hpp \
				gamma_shape_updater.hpp \
				updater.hpp \
				chain.hpp \
				output_manager.hpp \
				dirichlet_updater \
				statefreq_updater.hpp \
				exchangeability_updater.hpp \
				tree_updater.hpp \
				tree_length_updater.hpp \
				pwk.hpp
strom_CPPFLAGS = -std=c++11 -Wall \
				-I/usr/local/include/libhmsbeagle-1 \
				-I/usr/include \
				-I/usr/local/include \
				-I/usr/include/eigen3
strom_LDADD = -L$(HOME)/lib -lhmsbeagle \
				-L$(HOME)/lib/ncl -lncl \
				-L$(HOME)/Documents/libraries/boost_1_66_0/stage/lib -lboost_program_options
