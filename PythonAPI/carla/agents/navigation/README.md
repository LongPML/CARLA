# NAVIGATION

- `agent.py` contain situations that affect to the vehicle, include current ego state.
- `basic_agent.py` and `roaming_agnet.py` are two provied agent which have two types of difference missions.
- `global_route_planner.py` and `global_route_planner_dao.py` provided a long-term planning task like finding path, compute A* heuristic, turning decisions, ...
- `local_planner.py` contains a short-term planning include steering angle, ...
- Finaly, `controller` apply all planning to control vehicle.