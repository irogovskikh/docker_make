FROM gcc:13-bookworm AS build
WORKDIR /app/
COPY . .
RUN make -C /app/lib/ && make -C /app/apps/backend

FROM debian:bookworm-slim
WORKDIR /app
COPY --from=build /app/build/apps/backend .
CMD ./backend
