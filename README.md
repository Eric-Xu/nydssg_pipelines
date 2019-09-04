Summary:

As a prediction model grows in complexity, scikit-learn's `Pipeline` module and `FeatureUnion` module offers a convenient way to organize all of our data extraction, transformation, normalization, and training steps. By chaining transformers and estimators together, we can extract features into a single unit pipeline. Each feature pipeline can then be reordered and combined using `FeatureUnion`. This not only saves time, but allows us to keep our code better organized, while we look for the ideal combination of techniques for solving a modeling task.
