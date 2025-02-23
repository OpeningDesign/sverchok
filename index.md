> ### This file is parsed by menu.py
>
> The following strict rules apply to editing this file:
>
> - do not use tabs, anywhere
> - indent the Node's line using 4 spaces
> - if you aren't sure, follow the existing convention
>
> Failing to follow these points will break the node category parser.

## Generator
    SvLineNodeMK4
    SvSegmentGenerator
    SvPlaneNodeMk3
    SvNGonNode
    SvBoxNodeMk2
    SvCircleNode
    SvCylinderNodeMK2
    SphereNode
    SvIcosphereNode
    SvTorusNodeMK2
    SvSuzanneNode
    SvCricketNode
    ---
    BasicSplineNode
    SvQuadraticSplineNode
    svBasicArcNode
    RandomVectorNodeMK3
    SvScriptNodeLite
    SvSNFunctorB
    ImageNode

## Generators Extended
    SvBoxRoundedNode
    SvBricksNode
    SvPolygonGridNode
    HilbertNode
    Hilbert3dNode
    HilbertImageNode
    SvProfileNodeMK3
    SvMeshEvalNode
    SvReceiveFromSorcarNode
    SvGenerativeArtNode
    SvImageComponentsNode
    SvWFCTextureNode
    SvTorusKnotNodeMK2
    SvRingNodeMK2
    SvEllipseNodeMK2
    SvSuperEllipsoidNode
    SvRegularSolid
    SvConicSectionNode
    SvTriangleNode
    SvPentagonTilerNode
    SvSpiralNodeMK2

## Curves @ Primitives
    SvExLineCurveNode
    SvExCircleNode
    SvEllipseCurveNode
    SvRoundedRectangleNode
    SvArc3ptCurveNode
    SvArcSedCurveNode
    SvExCatenaryCurveNode
    SvFreeCadHelixNode
    ---
    SvExPolylineNode
    SvExFilletPolylineNode
    SvKinkyCurveNode
    SvBiArcNode
    SvPolyArcNode

## Curves @ NURBS
    SvExNurbsCurveNode
    SvApproxNurbsCurveMk2Node
    SvExInterpolateNurbsCurveNode
    SvDeconstructCurveNode

## Curves @ Bezier
    SvBezierSplineNode
    SvExBezierCurveFitNode

## Curves
    @ Primitives
    SvExCurveFormulaNode
    SvExCubicSplineNode
    SvTangentsCurveNode
    SvExRbfCurveNode
    SvExCirclifyNode
    @ Bezier
    @ NURBS
    ---
    SvExMarchingSquaresNode
    SvExMSquaresOnSurfaceNode
    ---
    SvExApplyFieldToCurveNode
    SvExCastCurveNode
    SvProjectCurveSurfaceNode
    SvOffsetCurveMk2Node
    SvCurveOffsetOnSurfaceNode
    SvExIsoUvCurveNode
    SvExCurveOnSurfaceNode
    ---
    SvExCurveLerpCurveNode
    SvSortCurvesNode
    SvExConcatCurvesNode
    SvExBlendCurvesMk2Node
    SvExFlipCurveNode
    SvReparametrizeCurveNode
    SvExSurfaceBoundaryNode
    ---
    SvExNearestPointOnCurveNode
    SvExOrthoProjectCurveNode
    SvExCurveEndpointsNode
    SvExCurveSegmentNode
    SvExCurveRangeNode
    SvExtendCurveNode
    SvSplitCurveNode
    SvExCurveLengthNode
    SvExCurveFrameNode
    SvCurveFrameOnSurfNode
    SvExCurveCurvatureNode
    SvExCurveTorsionNode
    SvExCurveExtremesNode
    SvExCurveZeroTwistFrameNode
    SvExSlerpCurveFrameNode
    SvExCurveLengthParameterNode
    SvLengthRebuildCurveNode
    SvExCrossCurvePlaneNode
    SvExCrossCurveSurfaceNode
    ---
    SvAdaptivePlotCurveNode
    SvExEvalCurveNode

## Surfaces @ NURBS
    SvExNurbsSurfaceNode
    SvExApproxNurbsSurfaceNode
    SvExInterpolateNurbsSurfaceNode
    SvNurbsLoftNode
    SvNurbsSweepNode
    SvNurbsBirailNode
    SvDeconstructSurfaceNode
    ---
    SvExQuadsToNurbsNode

## Surfaces
    SvExPlaneSurfaceNode
    SvExSphereNode
    SvExSurfaceFormulaNode
    SvInterpolatingSurfaceNode
    SvExMinimalSurfaceNode
    SvExMinSurfaceFromCurveNode
    @ NURBS
    ---
    SvExRevolutionSurfaceNode
    SvExTaperSweepSurfaceNode
    SvExExtrudeCurveVectorNode
    SvExExtrudeCurveCurveSurfaceNode
    SvExExtrudeCurvePointNode
    SvPipeSurfaceNode
    SvExCurveLerpNode
    SvExSurfaceLerpNode
    SvCoonsPatchNode
    SvBlendSurfaceNode
    SvExApplyFieldToSurfaceNode
    ---
    SvExSurfaceDomainNode
    SvExSurfaceSubdomainNode
    SvFlipSurfaceNode
    SvSwapSurfaceNode
    SvReparametrizeSurfaceNode
    SvSurfaceNormalsNode
    SvSurfaceGaussCurvatureNode
    SvSurfaceCurvaturesNode
    SvExSurfaceExtremesNode
    SvExNearestPointOnSurfaceNode
    SvExOrthoProjectSurfaceNode
    SvExRaycastSurfaceNode
    ---
    SvExImplSurfaceRaycastNode
    SvExMarchingCubesNode
    ---
    SvExTessellateTrimSurfaceNode
    SvAdaptiveTessellateNode
    SvExEvalSurfaceNode

## Fields
    SvCoordScalarFieldNode
    SvExScalarFieldFormulaNode
    SvExVectorFieldFormulaNode
    SvExComposeVectorFieldNode
    SvExDecomposeVectorFieldNode
    SvExScalarFieldPointNode
    SvAttractorFieldNodeMk2
    SvExImageFieldNode
    SvExMeshNormalFieldNode
    SvExVoronoiFieldNode
    SvExMinimalScalarFieldNode
    SvExMinimalVectorFieldNode
    SvExNoiseVectorFieldNode
    ---
    SvExScalarFieldMathNode
    SvExVectorFieldMathNode
    SvScalarFieldCurveMapNode
    SvExFieldDiffOpsNode
    SvScalarFieldCurvatureNode
    SvExMergeScalarFieldsNode
    ---
    SvExBendAlongCurveFieldNode
    SvExBendAlongSurfaceFieldNode
    ---
    SvExScalarFieldEvaluateNode
    SvExVectorFieldEvaluateNode
    SvExVectorFieldApplyNode
    ---
    SvExVectorFieldGraphNode
    SvExVectorFieldLinesNode
    SvExScalarFieldGraphNode

## Solids @ Make Face
    SvSolidPolygonFaceNode
    SvSolidWireFaceNode
    SvProjectTrimFaceNode

## Solids @ Analyze
   SvSolidValidateNode
   SvRefineSolidNode
   SvIsSolidClosedNode
   SvSolidCenterOfMassNode
   SvSolidFaceAreaNode
   SvSolidAreaNode
   SvSolidVolumeNode
   SvSolidBoundBoxNode

## Solids
   SvBoxSolidNode
   SvCylinderSolidNode
   SvConeSolidNode
   SvSphereSolidNode
   SvToursSolidNode
   @ Make Face
   SvSolidFaceExtrudeNode
   SvSolidFaceSolidifyNode
   SvSolidFaceRevolveNode
   SvSweepSolidFaceNode
   SvRuledSolidNode
   SvSolidFromFacesNode
   ---
   SvTransformSolidNode
   SvChamferSolidNode
   SvFilletSolidNode
   SvSolidBooleanNode
   SvSolidGeneralFuseNode
   SvMirrorSolidNode
   SvOffsetSolidNode
   SvSplitSolidNode
   SvHollowSolidNode
   ---
   SvIsInsideSolidNode
   SvSolidDistanceNode
   SvSliceSolidNode
   SvMeshToSolidNode
   SvSolidToMeshNodeMk2
   SvSolidVerticesNode
   SvSolidEdgesNode
   SvSolidFacesNode
   SvSelectSolidNode
   SvCompoundSolidNode
   @ Analyze
   SvSolidViewerNode

## Analyzers
    SvBBoxNodeMk2
    SvComponentAnalyzerNode
    SvDiameterNode
    SvVolumeNode
    SvAreaNode
    DistancePPNode
    SvDistancePointLineNode
    SvDistancePointPlaneNode
    SvDistancetLineLineNode
    SvPathLengthMk2Node
    SvOrigins
    GetNormalsNode
    VectorNormalNode
    SvIntersectLineSphereNode
    SvIntersectCircleCircleNode
    SvIntersectPlanePlaneNode
    SvKDTreeNodeMK2
    SvKDTreeEdgesNodeMK2
    SvKDTreePathNode
    SvBvhOverlapNodeNew
    SvMeshFilterNode
    SvEdgeAnglesNode
    SvPointInside
    SvProportionalEditNode
    SvWavePainterNode
    SvRaycasterLiteNode
    SvOBJInsolationNode
    SvDeformationNode
    SvLinkedVertsNode
    SvProjectPointToLine
    ---
    SvLinearApproxNode
    SvCircleApproxNode
    SvSphereApproxNode
    SvInscribedCircleNode
    SvSteinerEllipseNode
    ---
    SvMeshSelectNode
    SvSelectSimilarNode
    SvChessSelection

## Spatial
    SvHomogenousVectorField
    SvRandomPointsOnMesh
    SvPopulateSurfaceMk2Node
    SvPopulateSolidMk2Node
    SvFieldRandomProbeMk3Node
    ---
    DelaunayTriangulation2DNode
    SvDelaunay2DCdt
    SvDelaunay3dMk2Node
    ---
    Voronoi2DNode
    SvExVoronoi3DNode
    SvExVoronoiSphereNode
    SvVoronoiOnSurfaceNode
    SvVoronoiOnMeshNode
    SvVoronoiOnSolidNode
    ---
    SvLloyd2dNode
    SvLloyd3dNode
    SvLloydOnSphereNode
    SvLloydOnMeshNode
    SvLloydSolidNode
    SvLloydSolidFaceNode
    ---
    SvConvexHullNodeMK2
    SvConcaveHullNode

## Transforms
    SvMoveNodeMk3
    SvRotationNodeMk3
    SvScaleNodeMk3
    SvSymmetrizeNode
    SvMirrorNodeMk2
    MatrixApplyNode
    SvBarycentricTransformNode
    SvAlignMeshByMesh
    ---
    SvTransformSelectNode
    SvTransformMesh
    SvSimpleDeformNode
    SvBendAlongPathNode
    SvBendAlongSurfaceNode
    SvDisplaceNodeMk2
    SvNoiseDisplaceNode
    SvRandomizeVerticesNode
    SvCastNode
    SvFormulaDeformMK2Node

## Modifier Change
    SvDeleteLooseNode
    SvMergeByDistanceNode
    SvSeparateMeshNode
    SvSeparatePartsToIndexes
    SvLimitedDissolve
    SvPlanarFacesNode
    SvSplitFacesNode
    SvMeshBeautify
    SvTriangulateNode
    SvMakeMonotone
    ---
    PolygonBoomNode
    SvEdgeBoomNode
    SvDissolveMeshElements
    SvPols2EdgsNodeMk2
    SvMeshJoinNode
    ---
    SvFillsHoleNode
    SvRecalcNormalsNode
    SvFlipNormalsNode
    ---
    SvExtrudeEdgesNodeMk2
    SvExtrudeSeparateNode
    SvExtrudeRegionNode
    SvPokeFacesNode
    SvVertMaskNode
    SvSplitEdgesMk2Node
    SvRigidOrigamiNode
    ---
    SvFollowActiveQuads
    SvFlatGeometryNode

## Modifier Make
    LineConnectNodeMK2
    ---
    SvSubdivideNodeMK2
    SvOffsetLineNode
    SvContourNode
    ---
    SvDualMeshNode
    SvDiamondMeshNode
    SvClipVertsNode
    ---
    SvBevelCurveNode
    SvAdaptiveEdgeNode
    SvAdaptivePolygonsNodeMk2
    SvDuplicateAlongEdgeNode
    SvFractalCurveNode
    SvFrameworkNode
    SvSolidifyNode
    SvWireframeNode
    SvPipeNode
    SvMatrixTubeNode

## List Masks
    MaskListNode
    SvMaskJoinNode
    SvMaskConvertNode
    SvMaskToIndexNode
    SvIndexToMaskNode
    SvCalcMaskNode

## List Mutators
    SvListModifierNode
    SvUniqueItemsNode
    SvFixEmptyObjectsNode
    SvDatetimeStrings
    SvVDAttrsNodeMk2
    SvPolygonSortNode
    SvFindClosestValue
    SvMultiCacheNode

## List Main
    ListJoinNode
    SvConstantListNode
    ZipNode
    ListLevelsNode
    ListLengthNode
    ListSumNodeMK2
    ListMatchNode
    ListFuncNode
    SvListDecomposeNode
    SvListStatisticsNode

## List Struct
    ShiftNodeMK2
    ListRepeaterNode
    ListSliceNode
    SvListSplitNode
    ListFLNode
    SvListItemNode
    SvListItemInsertNode
    ListReverseNode
    ListShuffleNode
    SvListSortNode
    ListFlipNode
    SvListLevelsNode

## Dictionary
    SvDictionaryIn
    SvDictionaryOut

## CAD
    SvBevelNode
    SvIntersectEdgesNodeMK2
    SvOffsetNode
    SvInsetSpecial
    SvInsetFaces
    SvLatheNode
    SvSmoothNode
    SvSmoothLines
    ---
    CrossSectionNode
    SvBisectNode
    SvCutObjBySurfaceNode
    SvEdgesToFaces2D
    SvMergeMesh2D
    SvMergeMesh2DLite
    SvCropMesh2D
    SvWafelNode

## Number
    SvNumberNode
    SvScalarMathNodeMK4
    SvGenNumberRange
    SvListInputNode
    SvRndNumGen
    RandomNode
    Float2IntNode
    ---
    SvExecNodeMod
    SvMapRangeNode
    SvEasingNode
    SvCurveMapperNode
    SvMixNumbersNode
    SvMixInputsNode
    SvFormulaNodeMk3
    SvFormulaInterpolateNode
    ---
    SvGenFibonacci
    SvGenExponential
    SvOscillatorNode
    SvSmoothNumbersNode

## Vector
    GenVectorsNode
    VectorsOutNode
    SvAxisInputNodeMK2
    SvVectorMathNodeMK3
    VertsDelDoublesNode
    SvVectorRewire
    ---
    SvVertSortNode
    SvQuadGridSortVertsNode
    VectorDropNode
    VectorPolarInNode
    VectorPolarOutNode
    SvAttractorNode
    ---
    SvVectorLerp
    SvInterpolationStripesNode
    SvInterpolationNodeMK3
    SvInterpolationNodeMK2
    ---
    SvNoiseNodeMK2
    SvTurbulenceNode
    SvLacunarityNode
    SvVectorFractal

## Matrix
    SvMatrixInNodeMK4
    MatrixOutNode
    SvMatrixApplyJoinNode
    SvIterateNode
    MatrixDeformNode
    SvMatrixValueIn
    SvMatrixEulerNode
    MatrixShearNode
    SvMatrixNormalNode
    SvMatrixTrackToNode
    SvMatrixMathNode
    MatrixInterpolationNode

## Quaternion
    SvQuaternionInNodeMK2
    SvQuaternionOutNodeMK2
    SvQuaternionMathNode
    SvRotationDifference

## Logic
    SvLogicNode
    SvSwitchNodeMK2
    SvInputSwitchNodeMOD
    SvNeuroElman1LNode
    SvCustomSwitcher
    SvRangeSwitchNode
    ---
    SvLoopInNode
    SvLoopOutNode
    ---
    SvEvolverNode
    SvGenesHolderNode

## Viz
    Sv3DviewPropsNode
    ---
    SvViewerDrawMk4
    SvMatrixViewer28
    SvIDXViewer28
    SvViewer2D
    ---
    SvMeshViewer
    SvCurveViewerNodeV28
    SvPolylineViewerNode
    SvTypeViewerNodeV28
    SvSkinViewerNodeV28
    SvMetaballOutNode
    SvNurbsCurveOutNode
    SvNurbsSurfaceOutNode
    SvInstancerNodeMK3
    SvLightViewerNode
    ---
    SvGreasePencilStrokes
    SvEmptyOutNode
    ---
    SvTextureViewerNode
    SvTextureViewerNodeLite
    SvWaveformViewer
    SvConsoleNode

## Text
    ViewerNodeTextMK3
    SvDataShapeNode
    SvStethoscopeNodeMK2
    SvDebugPrintNode
    ---
    SvTextInNodeMK2
    SvTextOutNodeMK2
    ---
    NoteNode
    SvGTextNode

## BPY Data
    SvGetPropNode
    SvSetPropNode
    SvObjRemoteNodeMK2
    SvNodeRemoteNodeMK2
    SvGetAssetPropertiesMK2
    SvSetDataObjectNodeMK2
    SvSortObjsNode
    SvFilterObjsNode
    SvObjectToMeshNodeMK2
    SvPointOnMeshNodeMK2
    SvOBJRayCastNodeMK2
    SvSCNRayCastNodeMK2

## Scene
    SvObjectsNodeMK3
    SvObjInLite
    SvCurveInputNode
    SvFCurveInNodeMK1
    SvCollectionPicker
    SvBezierInNode
    SvExNurbsInNode
    ---
    SvSelectionGrabberLite
    SvObjEdit
    ---
    SvFrameInfoNodeMK2
    SvTimerNode
    ---
    SvDupliInstancesMK4

## Objects
    SvVertexGroupNodeMK2
    SvVertexColorNodeMK3
    SvAssignMaterialListNode
    SvMaterialIndexNode
    SvSetCustomUVMap

## Exchange
    SvExNurbsToJsonNode
    SvExJsonToNurbsNode
    SvImportSolidNode
    SvExportSolidNode

## Network
    UdpClientNode
    SvFilePathNode

## Layout
    WifiInNode
    WifiOutNode
    NodeReroute
    ConverterNode

## Pulga Physics
    SvPulgaPhysicsSolverNode
    SvPulgaVectorForceNode
    SvPulgaSpringsForceNode
    SvPulgaDragForceNode
    SvPulgaPinForceNode
    SvPulgaTimedForceNode
    SvPulgaCollisionForceNode
    SvPulgaAttractionForceNode
    SvPulgaAlignForceNode
    SvPulgaFitForceNode
    SvPulgaObstacleForceNode
    SvPulgaRandomForceNode
    SvPulgaBoundingBoxForceNode
    SvPulgaInflateForceNode
    SvPulgaAttractorsForceNodeMk2
    SvPulgaAngleForceNode
    SvPulgaVortexForceNode
    SvPulgaPhysicsNode

## SVG
    SvSvgDocumentNode
    SvSvgCircleNode
    SvSvgPathNodeMk2
    SvSvgMeshNode
    SvSvgTextNode
    SvSvgDimensionNode
    SvSvgGroupNode
    SvSvgFillStrokeNodeMk2
    SvSvgPatternNode

## Beta Nodes
    SvFormulaShapeNode
    SvHeavyTriangulateNode
    SvMeshUVColorNode
    SvUVPointonMeshNode
    SvSampleUVColorNode
    SvSubdivideLiteNode
    SvExtrudeSeparateLiteNode
    SvBVHnearNewNode
    SvUnsubdivideNode
    SvLimitedDissolveMK2
    SvArmaturePropsNode
    SvLatticePropsNode
    ---
    SvColorsInNodeMK1
    SvColorInputNode
    SvColorsOutNodeMK1
    SvFormulaColorNode
    SvTextureEvaluateNodeMk2
    SvColorRampNode
    SvColorMixNode
    ---
    SvSculptMaskNode
    SvSelectMeshVerts
    SvSetCustomMeshNormals
    ---
    SvCombinatoricsNode
    SvFormulaNodeMk4    

## Alpha Nodes
    SvBManalyzinNode
    SvBMObjinputNode
    SvBMoutputNode
    SvBMtoElementNode
    SvBMOpsNodeMK2
    ---
    SvCSGBooleanNodeMK2
    SvNumpyArrayNode
    SvParticlesMK2Node
    SvJoinTrianglesNode
    SvListSliceLiteNode
    SvCacheNode
    SvUVtextureNode
    SvSeparateMeshNodeMK2
    SvMultiExtrudeAlt
    SvPlanarEdgenetToPolygons
    SvTopologySimple
    SvSweepModulator
    ---
    SvGetPropNodeMK2
    SvSetPropNodeMK2
