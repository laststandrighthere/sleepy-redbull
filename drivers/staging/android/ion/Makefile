# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_ION) +=	ion-alloc.o
CFLAGS_ion.o = -I$(src)
ion-alloc-objs += ion.o ion_heap.o \
			ion_page_pool.o ion_system_heap.o \
			ion_carveout_heap.o ion_chunk_heap.o \
			ion_system_secure_heap.o ion_cma_heap.o \
			ion_secure_util.o ion_cma_secure_heap.o msm/msm_ion_of.o

