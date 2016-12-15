include_directories ("${PROJECT_SOURCE_DIR}/ta_abstract")
include_directories ("${PROJECT_SOURCE_DIR}/../include")

add_library (ta_abstract OBJECT ta_group_idx.c 
	ta_def_ui.c 
	ta_abstract.c 
	ta_func_api.c
	frames/ta_frame.c
	tables/table_a.c 
	tables/table_b.c 
	tables/table_c.c 
	tables/table_d.c 
	tables/table_e.c 
	tables/table_f.c 
	tables/table_g.c 
	tables/table_h.c 
	tables/table_i.c 
	tables/table_j.c 
	tables/table_k.c 
	tables/table_l.c 
	tables/table_m.c 
	tables/table_n.c 
	tables/table_o.c 
	tables/table_p.c 
	tables/table_q.c 
	tables/table_r.c 
	tables/table_s.c 
	tables/table_t.c 
	tables/table_u.c 
	tables/table_v.c 
	tables/table_w.c 
	tables/table_x.c 
	tables/table_y.c 
	tables/table_z.c
    )
include_directories ("${PROJECT_SOURCE_DIR}/ta_abstract/frames")
include_directories ("${PROJECT_SOURCE_DIR}/ta_common")
