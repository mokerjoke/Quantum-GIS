#TODO: Need to configure cmake to run pyrcc4 and pyuic4 as required when the resource
#      file or the ui change
SET(ICON_FILES
analysis.png
geometry.png
sampling.png
basic_statistics.png
geoprocessing.png
select_location.png
buffer.png
help.png
simplify.png
centroids.png
intersections.png
single_to_multi.png
check_geometry.png
intersect.png
split_layer.png
clip.png
join_attributes.png
sub_selection.png
convex_hull.png
join_location.png
sum_lines.png
define_projection.png
management.png
sum_points.png
difference.png
matrix.png
sym_difference.png
dissolve.png
mean.png
to_lines.png
export_geometry.png
multi_to_single.png
union.png
export_projection.png
neighbour.png
unique.png
extract_nodes.png
random_points.png
vector_grid.png
random_selection.png
ftools_logo.png
regular_points.png
delaunay.png
layer_extent.png
merge_shapes.png
)
INSTALL(FILES ${ICON_FILES} DESTINATION ${QGIS_DATA_DIR}/python/plugins/fTools/icons/default)
