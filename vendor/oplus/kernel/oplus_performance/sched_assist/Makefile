obj-y += sched_assist_common.o
obj-y += sched_assist_mutex.o
obj-y += sched_assist_rwsem.o
obj-y += sched_assist_futex.o
obj-y += sched_assist_workqueue.o
obj-$(CONFIG_LOCKING_PROTECT) += sched_assist_locking.o


ifeq ($(VERSION).$(PATCHLEVEL), 5.4)
obj-y += sched_assist_slide.o
endif
