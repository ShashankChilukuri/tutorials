PyTorch Prototype Recipes
---------------------------------------------
Prototype features are not available as part of binary distributions like PyPI or Conda (except maybe behind run-time flags). To test these features we would, depending on the feature, recommend building from master or using the nightly wheels that are made available on `pytorch.org <https://pytorch.org>`_.

*Level of commitment*: We are committing to gathering high bandwidth feedback only on these features. Based on this feedback and potential further engagement between community members, we as a community will decide if we want to upgrade the level of commitment or to fail fast.


.. raw:: html

        </div>
    </div>

    <div id="tutorial-cards-container">

    <nav class="navbar navbar-expand-lg navbar-light tutorials-nav col-12">
        <div class="tutorial-tags-container">
            <div id="dropdown-filter-tags">
                <div class="tutorial-filter-menu">
                    <div class="tutorial-filter filter-btn all-tag-selected" data-tag="all">All</div>
                </div>
            </div>
        </div>
    </nav>

    <hr class="tutorials-hr">

    <div class="row">

    <div id="tutorial-cards">
    <div class="list">

.. Add prototype tutorial cards below this line

.. Sparsity

.. customcarditem::
   :header: (prototype) Accelerating BERT with semi-structured (2:4) sparsity
   :card_description: Prune BERT to be 2:4 sparse and accelerate for inference.
   :image: _static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: prototype/semi_structured_sparse.html
   :tags: Model-Optimiziation

.. Mobile

.. customcarditem::
   :header: Use iOS GPU in PyTorch
   :card_description: Learn how to run your models on iOS GPU.
   :image: ../_static/img/thumbnails/cropped/ios.png
   :link: ../prototype/ios_gpu_workflow.html
   :tags: Mobile

.. customcarditem::
   :header: Convert MobileNetV2 to NNAPI
   :card_description: Learn how to prepare a computer vision model to use Android’s Neural Networks API (NNAPI).
   :image: ../_static/img/thumbnails/cropped/android.png
   :link: ../prototype/nnapi_mobilenetv2.html
   :tags: Mobile

.. customcarditem::
   :header: PyTorch Vulkan Backend User Workflow
   :card_description: Learn how to use the Vulkan backend on mobile GPUs.
   :image: ../_static/img/thumbnails/cropped/android.png
   :link: ../prototype/vulkan_workflow.html
   :tags: Mobile

.. customcarditem::
   :header: Tracing-based Selective Build Mobile Interpreter in Android and iOS
   :card_description: Learn how to optimize the mobile interpreter size with a tracing-based selective build.
   :image: ../_static/img/thumbnails/cropped/mobile.png
   :link: ../prototype/tracing_based_selective_build.html
   :tags: Mobile

.. customcarditem::
   :header: Convert Mobilenetv2 to Core ML
   :card_description: Learn how to prepare a computer vision model to use the PyTorch Core ML mobile backend.
   :image: ../_static/img/thumbnails/cropped/ios.png
   :link: ../prototype/ios_coreml_workflow.html
   :tags: Mobile

.. Modules

.. customcarditem::
   :header: Skipping Module Parameter Initialization in PyTorch 1.10
   :card_description: Describes skipping parameter initialization during module construction in PyTorch 1.10, avoiding wasted computation.
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/skip_param_init.html
   :tags: Modules

.. TorchScript

.. customcarditem::
   :header: Model Freezing in TorchScript
   :card_description: Freezing is the process of inlining Pytorch module parameters and attributes values into the TorchScript internal representation.
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/torchscript_freezing.html
   :tags: TorchScript

.. vmap

.. customcarditem::
   :header: Using torch.vmap
   :card_description: Learn about torch.vmap, an autovectorizer for PyTorch operations.
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/vmap_recipe.html
   :tags: vmap

.. NestedTensor

.. customcarditem::
   :header: Nested Tensor
   :card_description: Learn about nested tensors, the new way to batch heterogeneous-length data
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/nestedtensor.html
   :tags: NestedTensor

.. MaskedTensor

.. customcarditem::
   :header: MaskedTensor Overview
   :card_description: Learn about masked tensors, the source of truth for specified and unspecified values
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/maskedtensor_overview.html
   :tags: MaskedTensor

.. customcarditem::
   :header: Masked Tensor Sparsity
   :card_description: Learn about how to leverage sparse layouts (e.g. COO and CSR) in MaskedTensor
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/maskedtensor_sparsity.html
   :tags: MaskedTensor

.. customcarditem::
   :header: Masked Tensor Advanced Semantics
   :card_description: Learn more about Masked Tensor's advanced semantics (reductions and comparing vs. NumPy's MaskedArray)
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/maskedtensor_advanced_semantics.html
   :tags: MaskedTensor

.. customcarditem::
   :header: MaskedTensor: Simplifying Adagrad Sparse Semantics
   :card_description: See a showcase on how masked tensors can enable sparse semantics and provide for a cleaner dev experience
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/maskedtensor_adagrad.html
   :tags: MaskedTensor

.. Model-Optimization

.. customcarditem::
   :header: Inductor Cpp Wrapper Tutorial
   :card_description: Speed up your models with Inductor Cpp Wrapper
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/inductor_cpp_wrapper_tutorial.html
   :tags: Model-Optimization

.. customcarditem::
   :header: Inductor Windows CPU Tutorial
   :card_description: Speed up your models with Inductor On Windows CPU
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/inductor_windows.html
   :tags: Model-Optimization

.. customcarditem::
   :header: Use max-autotune compilation on CPU to gain additional performance boost
   :card_description: Tutorial for max-autotune mode on CPU to gain additional performance boost
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/max_autotune_on_CPU_tutorial.html
   :tags: Model-Optimization

.. Distributed
.. customcarditem::
   :header: Flight Recorder Tutorial
   :card_description: Debug stuck jobs easily with Flight Recorder
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/flight_recorder_tutorial.html
   :tags: Distributed, Debugging, FlightRecorder

.. customcarditem::
   :header: Context Parallel Tutorial
   :card_description: Parallelize the attention computation along sequence dimension
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/context_parallel.html
   :tags: Distributed, Context Parallel

.. Integration
.. customcarditem::
   :header: Out-of-tree extension autoloading in Python
   :card_description: Learn how to improve the seamless integration of out-of-tree extension with PyTorch based on the autoloading mechanism.
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/python_extension_autoload.html
   :tags: Extending-PyTorch, Frontend-APIs

.. GPUDirect Storage
.. customcarditem::
   :header: (prototype) Using GPUDirect Storage
   :card_description: Learn how to use GPUDirect Storage in PyTorch.
   :image: ../_static/img/thumbnails/cropped/generic-pytorch-logo.png
   :link: ../prototype/gpu_direct_storage.html
   :tags: GPUDirect-Storage

.. End of tutorial card section

.. raw:: html

    </div>

    <div class="pagination d-flex justify-content-center"></div>

    </div>

    </div>

.. -----------------------------------------
.. Page TOC
.. -----------------------------------------
.. toctree::
   :hidden:

   prototype/context_parallel.html
   prototype/flight_recorder_tutorial.html
   prototype/inductor_cpp_wrapper_tutorial.html
   prototype/inductor_windows.html
   prototype/ios_gpu_workflow.html
   prototype/nnapi_mobilenetv2.html
   prototype/tracing_based_selective_build.html
   prototype/ios_coreml_workflow.html
   prototype/numeric_suite_tutorial.html
   prototype/torchscript_freezing.html
   prototype/vmap_recipe.html
   prototype/vulkan_workflow.html
   prototype/nestedtensor.html
   prototype/maskedtensor_overview.html
   prototype/maskedtensor_sparsity.html
   prototype/maskedtensor_advanced_semantics.html
   prototype/maskedtensor_adagrad.html
   prototype/python_extension_autoload.html
   prototype/max_autotune_CPU_with_gemm_template_tutorial.html
