# private-OMPL-Tutorials
  #This is my own OMPL Tutorials
   ##(1)ompl::base::Cost -> double v_;{value()-> return v_};<br />
   ##(2)    Constructs an edge from a parent, a child, and (f-value,h-value or g-value) the value you want to evalue the edge cost. <br />
                Edge(const std::shared_ptr<Vertex> &parent, const std::shared_ptr<Vertex> &child,
                     const std::array<ompl::base::Cost, 3u> ); <br />
   ##(3) using EdgeQueue = ompl::BinaryHeap<Edge,std::function<bool(const Edge &, const Edge &)>>;<br />
