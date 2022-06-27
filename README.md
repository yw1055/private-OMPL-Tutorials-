# Private-OMPL-Tutorials
  # This is my own OMPL Tutorials<br />
   ## (1)   ompl::base::Cost -> double v_;{value()-> return v_};<br />
   ##(2)   Constructs an edge from a parent, a child, and the value you want to evaluate the edge cost, such as f,h,g: <br />
                Edge(shared_ptr<Vertex> &parent, shared_ptr<Vertex> &child,const array<ompl::base::Cost, 3u> ); <br />
   ##(3)   Edge queue, a priority queue for all edges on the motion tree: <br />
   using EdgeQueue = ompl::BinaryHeap<Edge,std::function<bool(const Edge &, const Edge &)>>;<br />
