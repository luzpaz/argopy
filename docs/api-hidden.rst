.. Generate API reference pages, but don't display these in tables.
.. This extra page is a work around for sphinx not having any support for
.. hiding an autosummary table.

.. autosummary::
    :toctree: generated/

    argopy

    argopy.fetchers
    argopy.fetchers.ArgoDataFetcher
    argopy.fetchers.ArgoDataFetcher.region
    argopy.fetchers.ArgoDataFetcher.float
    argopy.fetchers.ArgoDataFetcher.profile
    argopy.fetchers.ArgoDataFetcher.load
    argopy.fetchers.ArgoDataFetcher.to_xarray
    argopy.fetchers.ArgoDataFetcher.to_dataframe
    argopy.fetchers.ArgoDataFetcher.to_index
    argopy.fetchers.ArgoDataFetcher.plot
    argopy.fetchers.ArgoDataFetcher.uri
    argopy.fetchers.ArgoDataFetcher.data
    argopy.fetchers.ArgoDataFetcher.index
    argopy.fetchers.ArgoDataFetcher.dashboard
    argopy.fetchers.ArgoDataFetcher.clear_cache

    argopy.fetchers.ArgoIndexFetcher
    argopy.fetchers.ArgoIndexFetcher.region
    argopy.fetchers.ArgoIndexFetcher.float
    argopy.fetchers.ArgoIndexFetcher.profile
    argopy.fetchers.ArgoIndexFetcher.load
    argopy.fetchers.ArgoIndexFetcher.to_xarray
    argopy.fetchers.ArgoIndexFetcher.to_dataframe
    argopy.fetchers.ArgoIndexFetcher.to_csv
    argopy.fetchers.ArgoIndexFetcher.plot
    argopy.fetchers.ArgoIndexFetcher.index
    argopy.fetchers.ArgoIndexFetcher.clear_cache

    argopy.data_fetchers.erddap_data.ErddapArgoDataFetcher
    argopy.data_fetchers.erddap_data.Fetch_wmo
    argopy.data_fetchers.erddap_data.Fetch_box

    argopy.data_fetchers.localftp_data.LocalFTPArgoDataFetcher
    argopy.data_fetchers.localftp_data.Fetch_wmo
    argopy.data_fetchers.localftp_data.Fetch_box

    argopy.data_fetchers.argovis_data.ArgovisDataFetcher
    argopy.data_fetchers.argovis_data.Fetch_wmo
    argopy.data_fetchers.argovis_data.Fetch_box

    argopy.options.set_options

    argopy.tutorial.open_dataset

    argopy.utilities.monitor_status
    argopy.utilities.show_versions
    argopy.utilities.show_options
    argopy.utilities.clear_cache
    argopy.utilities.list_available_data_src
    argopy.utilities.list_available_index_src
    argopy.utilities.Chunker

    argopy.utilities.TopoFetcher
    argopy.utilities.TopoFetcher.cname
    argopy.utilities.TopoFetcher.define_constraints
    argopy.utilities.TopoFetcher.get_url
    argopy.utilities.TopoFetcher.load
    argopy.utilities.TopoFetcher.to_xarray
    argopy.utilities.TopoFetcher.cachepath
    argopy.utilities.TopoFetcher.uri

    argopy.utilities.list_standard_variables
    argopy.utilities.list_multiprofile_file_variables
    argopy.utilities.check_localftp
    argopy.utilities.format_oneline
    argopy.utilities.is_box
    argopy.utilities.is_indexbox
    argopy.utilities.is_wmo
    argopy.utilities.check_wmo
    argopy.utilities.wmo2box

    argopy.plotters.open_dashboard
    argopy.plotters.bar_plot
    argopy.plotters.plot_trajectory

    argopy.stores.filesystems.filestore
    argopy.stores.filestore.open_dataset
    argopy.stores.filestore.read_csv

    argopy.stores.filestore.open
    argopy.stores.filestore.glob
    argopy.stores.filestore.exists
    argopy.stores.filestore.store_path
    argopy.stores.filestore.register
    argopy.stores.filestore.cachepath
    argopy.stores.filestore.clear_cache
    argopy.stores.filestore.open_mfdataset

    argopy.stores.filesystems.httpstore
    argopy.stores.httpstore.open_json
    argopy.stores.httpstore.open_dataset
    argopy.stores.httpstore.read_csv
    argopy.stores.httpstore.open
    argopy.stores.httpstore.glob
    argopy.stores.httpstore.exists
    argopy.stores.httpstore.store_path
    argopy.stores.httpstore.register
    argopy.stores.httpstore.cachepath
    argopy.stores.httpstore.clear_cache
    argopy.stores.httpstore.open_mfdataset
    argopy.stores.httpstore.open_mfjson

    argopy.stores.filesystems.memorystore
    argopy.stores.memorystore.open
    argopy.stores.memorystore.glob
    argopy.stores.memorystore.exists
    argopy.stores.memorystore.store_path
    argopy.stores.memorystore.register
    argopy.stores.memorystore.cachepath
    argopy.stores.memorystore.clear_cache
    argopy.stores.memorystore.open_dataset
    argopy.stores.memorystore.open_mfdataset
    argopy.stores.memorystore.read_csv

    argopy.stores.argo_index.indexstore
    argopy.stores.argo_index.indexfilter_wmo
    argopy.stores.argo_index.indexfilter_box

    argopy.xarray.ArgoAccessor.point2profile
    argopy.xarray.ArgoAccessor.profile2point
    argopy.xarray.ArgoAccessor.cast_types
    argopy.xarray.ArgoAccessor.uid
    argopy.xarray.ArgoAccessor.filter_qc
    argopy.xarray.ArgoAccessor.filter_data_mode
    argopy.xarray.ArgoAccessor.interp_std_levels
    argopy.xarray.ArgoAccessor.teos10
